# 柱状図ツール

Excel のデータから地質柱状図を描くブラウザ用ツールです。インストール不要で、データはブラウザ内だけで処理されます。

- **コア柱状図メーカー**（`core-column.html`）… コア記載からコアを並べた柱状図を描く。構造の柄・記号、FGDC の岩相柄、マンセル色、PNG / SVG / Illustrator 用スクリプト出力
- **柱状図メーカー（地層）**（`strata-column.html`）… 層厚・深度の表から地層柱状図を描く。FGDC の岩相パターン、PNG / SVG 出力

岩相パターンは FGDC Digital Cartographic Standard for Geologic Map Symbolization（FGDC-STD-013-2006）第37節を参考に描き直したものです。

Excel の読み込みに [SheetJS](https://sheetjs.com/)（Apache License 2.0）を同梱しています。
