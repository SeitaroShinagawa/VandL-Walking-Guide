# Vision and Language (V&L) 研究の歩き方

このリポジトリは、Vision and Language (V&L)分野に興味のある方向けに、V&L研究の歩き方をまとめたものです。V&L研究の歩き方とは、V&L研究を始めるにあたって、どのような資料を読むと効率的に分野のことを理解できるのか、どのような視点で考えれば良い研究テーマを決めることができるかをまとめたものです。V&L研究を始めようと検討されている方が景気の良いスタートダッシュを切る一助になれば幸いです。

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Vision and Language (V\&L) 研究の歩き方](#vision-and-language-vl-研究の歩き方)
  - [1. まずは体系的に書かれた本を読むのが一番近道（チュートリアル関連本）](#1-まずは体系的に書かれた本を読むのが一番近道チュートリアル関連本)
  - [2. お金をかけたくなければor最近の話題について知りたいなら（Web上の良資料）](#2-お金をかけたくなければor最近の話題について知りたいならweb上の良資料)
    - [よくチュートリアル講演してる人の講演を時系列で読んでいくと感覚がつかめる](#よくチュートリアル講演してる人の講演を時系列で読んでいくと感覚がつかめる)
    - [大規模言語モデル](#大規模言語モデル)
  - [研究テーマを考えるコツ](#研究テーマを考えるコツ)
    - [やりたいこと・実現したいことから考える](#やりたいこと実現したいことから考える)
      - [コラム：  あまり思い浮かばない時の処方箋](#コラム--あまり思い浮かばない時の処方箋)
    - [重要とされている研究分野と組み合わせて考える](#重要とされている研究分野と組み合わせて考える)
    - [興味のある技術と組み合わせて考える](#興味のある技術と組み合わせて考える)
    - [使ってもらう利用者（人間）に注目する(Human Computer InteractionやHuman-in-the-loop)](#使ってもらう利用者人間に注目するhuman-computer-interactionやhuman-in-the-loop)
    - [自分の趣味や得意なことと組み合わせてドメイン知識を活かす](#自分の趣味や得意なことと組み合わせてドメイン知識を活かす)

<!-- /code_chunk_output -->

## 1. まずは体系的に書かれた本を読むのが一番近道（チュートリアル関連本）
- [キッチン・インフォマティクス 料理を支える自然言語処理と画像処理](https://www.ohmsha.co.jp/book/9784274226564/)
  - 料理を題材としてV&Lの基礎が学べる、平易に書かれているので機械学習に馴染みのない人にもとっつきやすいかも
- [コンピュータビジョン最前線　Winter 2021](https://www.kyoritsu-pub.co.jp/book/b10003371.html) 
  - 品川の『ニュウモン Vision and Language』は、深層学習時代のV&LがTransformerベースになってきた2021年頃までの大きな流れと主要な要素技術を学べる。現物は既に絶版、電子書籍のみ
- [CVIMチュートリアル1](https://www.kyoritsu-pub.co.jp/book/b10031091.html) 
  - コンピュータビジョン最前線のニュウモン記事のまとめ。↑と同じ、『ニュウモン Vision and Language』を収録
- [Vision Transformer入門](https://gihyo.jp/book/2022/978-4-297-13058-9)
  - Vision Transformer (ViT)の基礎と応用を学べる。V&LにおけるViTの応用についても網羅的に解説されている

## 2. お金をかけたくなければor最近の話題について知りたいなら（Web上の良資料）
メモ：SlideshareはNotionに埋め込むと広告を表示させないで見ることができます。

- [人工知能学会私のブックマーク シリーズ](https://www.ai-gakkai.or.jp/resource/my-bookmark/)
  - [視覚と自然言語の融合研究（Integrating Vision and Language）](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol32-no1/)
  - [Language and Robotics研究会](https://sites.google.com/view/language-and-robotics/)

### よくチュートリアル講演してる人の講演を時系列で読んでいくと感覚がつかめる

牛久祥孝先生 [Speaker Deck](https://speakerdeck.com/yushiku/toaruhui-she-totoaruhui-she-tosoreyi-wai-falsehua), [Slideshare](https://www.slideshare.net/YoshitakaUshiku/presentations)
画像理解のモチベーションから近年までのVision and Languageへの展開が分かる

- [視覚と対話の融合研究](https://www.slideshare.net/YoshitakaUshiku/ss-123687543)
- [2019.03.07 これからの Vision & Language ～ Acadexit した4つの理由](https://www.slideshare.net/YoshitakaUshiku/vision-language-acadexit-4)
- [2020.10.26 機械学習を民主化する取り組み](https://www.slideshare.net/YoshitakaUshiku/ss-238968778)

西田京介先生 [Speaker Deck](https://speakerdeck.com/kyoun)
V&Lの基礎技術の他、特に文書画像理解について詳細な解説がある
- いっぱいあるので詳しくはURL参照

品川 [Speaker Deck](https://speakerdeck.com/sei88888), [Slideshare](https://www.slideshare.net/ShinagawaSeitaro/presentations)
深層学習時代のV&Lの基礎技術の使い方・使いどころを学べる
- [2022.12.17 第10回 Language and Robotics 研究会 講演資料](https://speakerdeck.com/sei88888/2022-dot-12-dot-17-di-10hui-language-and-robotics-yan-jiu-hui-jiang-yan-zi-liao)
- [2022.9.7 NAIST DSCサマーセミナー「Vision and Language技術の最新動向」](https://speakerdeck.com/sei88888/2022-dot-9-7-naist-dscsamasemina-vision-and-languageji-shu-nozui-xin-dong-xiang)
- [2022.2.11 第6回 統計・機械学習若手シンポジウム チュートリアル講演 Vision and LanguageとTransformers](https://speakerdeck.com/sei88888/2022-dot-2-11-di-6hui-tong-ji-ji-jie-xue-xi-ruo-shou-sinpoziumu-tiyutoriarujiang-yan-vision-and-languagetotransformers)
- [2021.05.21 Vision and Languageと分野を取り巻く深層学習手法の紹介](https://speakerdeck.com/sei88888/vision-and-languagetofen-ye-woqu-rijuan-kushen-ceng-xue-xi-shou-fa-falseshao-jie)

### 大規模言語モデル

- [大規模言語モデルの驚異と脅威](https://speakerdeck.com/chokkan/20230327_riken_llm)


## 研究テーマを考えるコツ

※関連する[人工知能学会私のブックマーク シリーズ](https://www.ai-gakkai.or.jp/resource/my-bookmark/)のリンクも添付します。  

### やりたいこと・実現したいことから考える
例：
- 視覚障がい者の人を助けるアプリを作りたい
- 自動運転を実現したい
- ロボットに代わりに働いて欲しい
- 汎用人工知能を実現したい

#### コラム：  あまり思い浮かばない時の処方箋
そうだ、ChatGPTに相談しよう。 次のようにしてChatGPTにネタ出しをしてもらうことができる。

戦略：
1. markdownでおおまかなタスクをリストアップしてもらう
2. 実応用例を何個か考えてもらう
3. それをマインドマップで出力させる

実際の操作：
1. プロンプトを入力「List up tasks of Vision and Language research in markdown.」
2. プロンプトを入力「OK. Next, list up 5 real application examples following each task.」
3. ChatGPTのUI横のコピーアイコンを押して、[markdownからマインドマップを生成してくれるサイト(markmap)](https://markmap.js.org/)に貼り付ける

出力例：
[ChatGPTによって生成されたテキストのコピー](application_mindmap.md)
[出力したhtml](application_mindmap.html)

### 重要とされている研究分野と組み合わせて考える
例：
- 説明可能性
  - [機械学習における解釈性（Interpretability in Machine Learning）](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol33-no3/)
  - [説明可能AI](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol34-no4/)
- 機械学習のバイアス・公平性
  - [人工知能と公平性](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol37-no2/)
- 生成AIにおけるhallucination(反事実の生成や湧きだしの問題)

  - [学習・コミュニケーション・言語の創発と進化に対する構成論的アプローチ](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol37-no5/)
  - [第一言語獲得から考える人工知能](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol38-no2/)


### 興味のある技術と組み合わせて考える
自分が誰よりも深く知っていると自信のある技術があると、別の研究題材やタスクに応用できたりするので強みになります。

例：
- ベイズ最適化
- 最適輸送
- 強化学習
- Scene Graph


### 使ってもらう利用者（人間）に注目する(Human Computer InteractionやHuman-in-the-loop)
Vision and Languageは人間とのインタラクションを前提とする分野でもあるので、教育への応用や人間の特性や認知バイアスを考慮した研究が必要です。 

  - [認知バイアス・ヒューリスティック：意思決定科学から見る人間らしさ](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol34-no3/)
  - [語彙学習支援システム](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol35-no2/)
  - [知的学習支援システム（Intelligent Tutoring Systems）](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol33-no4/)
  - [クラウドソーシングとヒューマンコンピュテーション（Crowdsourcing and Human Computation）](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol30-no1/)
  - [対話システム](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol36-no5/)
  - [対話システムと会話分析](ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol36-no6/)
  

### 自分の趣味や得意なことと組み合わせてドメイン知識を活かす
例：
  - [料理情報処理（Food Information Processing）](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol33-no1/)
  - [コミック工学（Comic Computing）](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol32-no6/)



