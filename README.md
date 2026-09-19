# カロリーノート サポートサイト

iOS アプリ「カロリーノート」のサポートページとプライバシーポリシー。
GitHub Pages で公開する（public）。

- `index.html` … 入口
- `support.html` … 使い方とよくある質問（App Store の「サポートURL」）
- `privacy.html` … プライバシーポリシー（App Store の「プライバシーポリシーURL」）

★ HealthKit を使うアプリはプライバシーポリシーが必須。
`privacy.html` の「Apple ヘルスケア（HealthKit）との連携について」にある

- ヘルスケアのデータを端末の外に出さない
- 広告・マーケティングに使わない

の2点は、App Store Review Guideline 5.1.3 で明示が求められる。**消さないこと。**

★ 医療・診断・治療をうたう表現は入れない。

**要確認**：HealthKit で実際に読み書きする項目は、アプリ本体ができたら
`privacy.html` の「読み取るもの／書き込むもの」と突き合わせて直すこと。
いまの記述はアプリの用途から書いたもので、実装を見て書いたものではない。

雛形は `kintore-support`。
