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

HealthKit で読み書きする項目は、**実装（fa5c604）に合わせてある**。

- 読み取り … 体重、体脂肪率
- 書き込み … 食事のエネルギー（kcal）、たんぱく質、脂質、炭水化物、体重

ほかの項目には許可を求めない。**実装を変えたらこのページも直すこと。**

雛形は `kintore-support`。
