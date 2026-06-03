# previews — 色・ビジュアル確認用ツール

設計上の色・形・アニメを**ブラウザで目視確認・チューニング**するための単体HTML。ビルド不要、ダブルクリックで開ける。
確定値は `docs/product/スコアリングモデル.md` §7（配色）と `docs/product/ビジュアルディレクション.md`（形・茎・咲くアニメ）が正本。

| ファイル | 用途 |
|---|---|
| [color-preview.html](color-preview.html) | ライトUI用インク変種。コントラスト目標スライダー1本で5色を一律導出し、白/紺背景で比較 |
| [stem-preview.html](stem-preview.html) | 茎・葉の色。紺の庭にライム/アクア花序を載せ、茎の明度・彩度・色相を振って「構造として沈むか」を確認 |
| [hydrangea-prototype.html](hydrangea-prototype.html) | 紫陽花の形の検討（手まり咲き/額咲き/ゆるい房・萼形状・hueDrift等）。Canvas実描画。Codexプロトタイプ由来 |
| [hydrangea-bloom.html](hydrangea-bloom.html) | 咲くアニメ（花火ブルーム）。茎が伸びる→葉→破裂→放射。手まり咲き×浅い切れ込み固定。静か/本気・二段破裂・Reduce Motion切替 |
