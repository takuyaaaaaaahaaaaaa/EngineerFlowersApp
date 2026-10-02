# previews — 色・ビジュアル確認用ツール

設計上の色・形・アニメを**ブラウザで目視確認・チューニング**するための単体HTML。ビルド不要、ダブルクリックで開ける。
確定値は `docs/product/タネと色.md` §7（配色）と `docs/product/ビジュアルディレクション.md`（形・茎・咲くアニメ）が正本。
`hydrangea-prototype.html` と `hydrangea-bloom.html` は2026-10の再設計より前のもので、量（花序数）や強度を変える操作が残っている。現在は量を測らないので、形と動きの参考として見る。

| ファイル | 用途 |
|---|---|
| [color-preview.html](color-preview.html) | ライトUI用インク変種。コントラスト目標スライダー1本で5色を一律導出し、白/紺背景で比較 |
| [stem-preview.html](stem-preview.html) | 茎・葉の色。紺の庭にライム/アクア花序を載せ、茎の明度・彩度・色相を振って「構造として沈むか」を確認 |
| [hydrangea-prototype.html](hydrangea-prototype.html) | 紫陽花の形の検討（手まり咲き/額咲き/ゆるい房・萼形状・hueDrift等）。Canvas実描画。Codexプロトタイプ由来 |
| [daily-cell-compare.html](daily-cell-compare.html) | 量の軸を廃止した後の「普段の日のマス」を、A（同じ大きさの紫陽花に色が混ざる）とC（草の色だけ変わる）で月30日・年365日に並べて比較。結果、月はA・年はCを採用。花の形は簡易描画 |
| [seed-flick.html](seed-flick.html) | タネをはじいて飛ばす手触りの試作。スマホで指で触る前提。手元のタネを上にはじくと今日のマスへ飛び、着地して育って咲く。2つ目以降は毬に色が足される。飛ぶ速さ・弧の高さ・育つ時間を調整できる |
| [hydrangea-bloom.html](hydrangea-bloom.html) | 咲くアニメ（花火ブルーム）。茎が伸びる→葉→破裂→放射。手まり咲き×浅い切れ込み固定。静か/本気・二段破裂・Reduce Motion切替 |
