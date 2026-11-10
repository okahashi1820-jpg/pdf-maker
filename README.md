# img2pdf

複数の画像を1つのPDFにまとめるWebアプリ(単一HTML)。変換はブラウザ内で完結し、画像は送信されません。

- 並べ替え・回転・削除
- 用紙サイズ(A4 / Letter / 画像サイズ)、余白、画質の設定
- PDF生成に [pdf-lib](https://pdf-lib.js.org/) を使用

公開: GitHub Pages(`index.html` を配信)

## PWA
`manifest.json` と `sw.js` によりインストール可能・オフライン動作。pdf-lib は `pdf-lib.min.js` として同梱(MIT)。
ファイルを更新したら `sw.js` の `VERSION` を上げてください。
