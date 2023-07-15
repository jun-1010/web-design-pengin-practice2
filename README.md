# ポートフォリオ02

## 1. サイトの概要

ポートフォリオ02は、HTML、CSS、JavaScriptで構築された静的なWebサイトです。

Cresta Designという架空の会社のポートフォリオを作成しています。

[PENGIN](https://pengi-n.co.jp/blog/coding-practice2/)さんが配布しているデザインカンプを実装したものです。

GitHub Pagesで公開中:[https://sim10play.github.io/portfolio02/](https://sim10play.github.io/portfolio02/)

## 2. ファイル構成

- index.html: ポートフォリオのメインページ
- header.html: ヘッダー部分のHTML
- footer.html: フッター部分のHTML
- contact-page.html: お問い合わせページのHTML
- css/style.css: PC向けのスタイルシート
- css/sp-style.css: スマートフォン向けのスタイルシート
- js/main.js: メインのJavaScriptファイル

## 3. 主な機能

3.1 レスポンシブデザイン: モバイルフレンドリーなデザインを採用しています。
3.2 スライダー: Swiper.jsを使用して、トップページのスライダーを実装しています。
3.3 メニューバー: ヘッダーにはメニューバーがあり、各セクションへのリンクがあります。
3.4 お問い合わせフォーム: お問い合わせページには、お問い合わせ内容を入力するフォームがあります。

## 4. 使用言語とツール

- HTML (バージョン: HTML5)
- CSS (バージョン: CSS3)
- JavaScript (バージョン: ES6)
- jQuery (バージョン: 3.6.0)
- フォント: Google Fontsの"Roboto Regular 400"と"Noto Sans Japanese Regular 400"
- リセットCSS: ress.min.css


## 5. JavaScriptの概要

js/main.jsは、メインのJavaScriptファイルです。以下のような機能が実装されています。

5.1 共通部分の読み込み:

- $("#header").load("./header.html")を使用して、ヘッダーのHTMLを読み込みます。
- $("#footer").load("./footer.html")を使用して、フッターのHTMLを読み込みます。

5.2 ヘッダーの背景色の切り替え:

- スクロールイベントを監視し、トップセクションを超えた場合にヘッダーの背景色にクラスを追加または削除します。
- $(window).on('scroll', function () { ... })を使用してスクロールイベントを処理します。

5.3 ハンバーガーメニューの表示と非表示の切り替え:

- ハンバーガーメニューボタンをクリックすると、ナビゲーションの表示と非表示を切り替えます。
- toggleNav()関数を使用して、ナビゲーションの表示状態を切り替えます。

5.4 ウィンドウサイズの変更に応じたナビゲーションの表示と非表示の切り替え:

- ウィンドウのリサイズイベントを監視し、ウィンドウサイズが一定の幅以下になった場合にナビゲーションの表示と非表示を切り替えます。
- window.onresizeイベントを使用して、ウィンドウのリサイズイベントを処理します。

詳細なJavaScriptのコードは提供されたmain.jsファイルをご確認ください。

以上がポートフォリオ02の概要です。詳細なファイル構成や各ファイルのコードは提供されたファイルを参照してください。
