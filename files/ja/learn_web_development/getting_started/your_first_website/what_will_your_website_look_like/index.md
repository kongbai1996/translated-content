---
title: ウェブサイトをどんな外見にするか
slug: Learn_web_development/Getting_started/Your_first_website/What_will_your_website_look_like
l10n:
  sourceCommit: 5b20f5f4265f988f80f513db0e4b35c7e0cd70dc
---

{{LearnSidebar}}

{{NextMenu("Learn_web_development/Getting_started/Your_first_website/Creating_the_content", "Learn_web_development/Getting_started/Your_first_website")}}

「_ウェブサイトをどんな外見にするか_」では、コードを書き始める前に、このウェブサイトについて計画したりデザインしたりすべき事柄について説明します。例えば「どんな情報をウェブサイトで提供するのか」「どのフォントや色を使いたいのか」「このウェブサイトは何をするのか」などです。

<table>
  <tbody>
    <tr>
      <th scope="row">前提条件:</th>
      <td>
        コンピューターのオペレーティングシステム、ウェブサイトを構築する際に使用する基本ソフトウェア、およびファイルシステムに概ね慣れておくこと。
      </td>
    </tr>
    <tr>
      <th scope="row">学習成果:</th>
      <td>
        <ul>
          <li>基本的なウェブサイトを計画すること。</li>
          <li>基本的なデザインプロセスを使うこと。</li>
          <li>資産を集めること。</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

## まず最初に: 計画を立てる

始める前に、いくつか考えておかなければいけないことがあります。このウェブサイトは実際に何をすべきでしょうか？普通ウェブサイトは様々なことができます。しかし、はじめは単純なことにとどめておくべきでしょう。まずは、見出し一つ、画像一つ、そしていくつかの段落のある単純なウェブページを作ることから始めましょう。

まずはじめに、次の質問に答える必要があります。

1. **何についてのウェブサイトですか？** 犬、ニューヨーク、それともパックマン？
2. **主題についてどんな情報を表現しようとしていますか？** タイトルといくつかの段落、それからページに表示させたい画像を考えます。
3. **ウェブサイトをどんな外見にしますか？** 簡単で大まかな言葉で言うと？背景色は？適切なフォントはフォーマル？漫画？太字で派手？繊細？

> [!NOTE]
> 複雑なプロジェクトでは、色、フォント、ページのアイテム間の余白、適切な文体など、詳細なガイドラインが必要です。これは、デザインガイド、デザインシステム、ブランドブックなどと呼ばれます。一例として、 [Firefox Acorn Design System](https://acorn.firefox.com/latest)があります。

## デザインをスケッチする

次に、ペンと紙を取って、あなたのサイトの見た目をどういう風にしたいのか、大まかに描き出します。はじめてのシンプルなウェブページでは、描き出すものもあまりないですが、ウェブサイトを作るうえでの習慣として身につけるべきです。ヴァン・ゴッホのようになる必要はありませんので！

![紙に描いたウェブサイトのラフ画とスケッチ](website-drawing-scan.png)

> [!NOTE]
> 現実の複雑なウェブサイトの場合でも、デザインチームは普通、ラフスケッチを描くことから始めます。その後、グラフィックエディターやウェブの技術を使って、デジタルのモックアップを作るのです。
>
> 多くの場合、ウェブの開発チームには、グラフィックデザイナーと{{Glossary("UX", "ユーザーエクスペリエンス")}} (UX) デザイナーがいます。グラフィックデザイナーは、ウェブサイトの見た目を作り上げます。 UX デザイナーは、もう少し抽象的な役割を持っていて、サイトを訪れるユーザーがウェブサイトでどういう経験をし、どのように操作するかということを考えます。

この時点で、最終的にウェブページに現れるコンテンツの用意を始めておくといいでしょう。早くから文章とタイトルを決めておいてください。これらを近くに置いておいてください。

### テーマカラーの選択

色を選ぶときは、[色選択ツール](/ja/docs/Web/CSS/CSS_colors/Color_picker_tool)へ行き、好みの色を見つけましょう。色をクリックすると、 `#660066` のような 6 桁の奇妙なコードが出てきます。これは*ヘキサコード*（16 進コード）と呼ばれ、選んだ色を表します。今はどこか安全なところにコピーしておきましょう。

![MDN Docs ウェブサイトのカラーピッカーツールで、RGB、HSL、HEX の色を利用できます](color-picker.png)

### 画像

画像を探すには、[Google 画像検索](https://www.google.com/imghp?gws_rd=ssl)にアクセスし、ぴったりなものを探しましょう。

1. 欲しい画像が見つかったら、クリックして拡大表示にします。
2. 画像を右クリック（Mac では Ctrl +クリック）し、\[名前を付けて画像を保存...] を選択して、画像を安全に保存する場所を選択します。または、後で使用するためにブラウザーのアドレスバーから画像のウェブアドレスをコピーします。

![Google 画像検索での検索語句の検索結果](updated-google-images.png)

なお、ウェブ上のほとんどの画像には、 Google 画像検索にあるものも含め、著作権があります。あなたが著作権を侵害してし舞うことを防ぐために、 Google のライセンスフィルターを使うと良いでしょう。 \[ツール] ボタンをクリックすると、 \[ライセンス] オプションが下に表示されます。「クリエイティブ・コモンズ ライセンス」などの選択肢を選択してください。

![Google 画像検索でクリエイティブ・コモンズ ライセンスの画像を取得するための検索結果のフィルタリング](updated-google-images-licensing.png)

### フォント

画像と同様に、多くのフォントはライセンスで保護されており、サイト内で自由に使用することはできません。[Google フォント](https://developers.google.com/fonts)は、Google が自分自身で所有するウェブサービスであり、たくさんのフォントにアクセスすることができます。

フォントが見つかったら、そのフォントを使用する方法は大きく分けて 2 つあります。

1. Google のサーバーからフォントを読み込むために、コードに参照を追加する。
2. 自分のシステムにフォントファイルをダウンロードし、フォントをホスティングし、ウェブサイトのコードでホスティングしたコピーを使用する。

> [!NOTE]
> Google フォントでホスティングされているフォントを提供すると、フォントサービスがユーザーの IP アドレスを公開するため、EU のデータプライバシー規則である [GDPR](https://gdpr.eu/what-is-gdpr) に抵触する可能性があります。これが問題になりそうな場合は、2 つ目の選択肢を選んでください。

また、Arial、Times New Roman、Courier New などの[セーフウェブフォント](https://web.mit.edu/jmorzins/www/fonts.html)を使用することもできます。

{{NextMenu("Learn_web_development/Getting_started/Your_first_website/Creating_the_content", "Learn_web_development/Getting_started/Your_first_website")}}
