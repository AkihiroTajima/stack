# Salesforce認定アドミニストレーター取得計画

作成日: 2026-06-12
上位目標: コンピュータサイエンスのすべてに精通する（生存戦略）

## 達成目標
- **Salesforce Certified Platform Administrator** に合格する
- 目標受験日: **2026年9月12日（土）前後**（今日から約13週）
  - ※マラソン本番が9/23のため、9月後半と重ならないよう中旬までに受験する設計。

## 試験要項（2025/12/15改定版・2026年現行）
- 形式: 選択式60問（採点対象）＋非採点5問／**制限105分**
- 合格ライン: **65%（60問中39問正解）**
- 出題8分野と配点（学習時間の配分根拠）:

| 分野 | 配点 | 重み |
| --- | --- | --- |
| Data & Analytics Management | 17% | 最重要 |
| Configuration & Setup | 15% | 大 |
| Object Manager & Lightning App Builder | 15% | 大 |
| Automation（Flow中心） | 15% | 大 |
| Sales & Marketing Applications | 10% | 中 |
| Service & Support Applications | 10% | 中 |
| Productivity & Collaboration | 10% | 中 |
| Agentforce AI（新設） | 8% | 新規・要補強 |

> 2026年改定の要点: Data&AnalyticsとAutomation/Flowの比重が上がり、**Agentforce AIが新設**。逆に旧来のConfiguration/Object Managerは各20%→15%に縮小。学習時間はこの配点に比例配分する。

## 使用教材
| 区分 | 教材 | 内容 | 言語 |
| --- | --- | --- | --- |
| **メイン講座** | [Complete Salesforce Certified Platform Administrator Course（Mike Wheeler）](https://www.udemy.com/course/salesforce-administrator/) | 18セクション・534講義・約39.6時間。8分野＋Agentforceを網羅。ChatGPT版／非ChatGPT版の2トラック＋模試60問付き。評価4.6（3.7万件） | 英語 |
| **バックアップ講座** | [salesforce-admin1](https://www.udemy.com/course/salesforce-admin1/) | メイン講座が言語的に厳しい場合の切り替え先 | 日本語想定 |
| **問題演習** | [Salesforce Certified Platform Admin – Practice Exam 2026（NextGen）](https://www.udemy.com/course/salesforce-certified-platform-admin-practice-exam-2026/) | 本番形式の時間制限テスト4本・計259問・全問解説付き。2026年最新仕様 | 英語 |

### 教材運用の方針
- **メイン講座は英語に取り組み、不自由があればバックアップ（日本語）に切り替える。**
- メイン講座は「ChatGPT版」と「非ChatGPT版」の2トラックで約39.6時間あるが、**どちらか一方だけ視聴すれば足りる（実質約17〜20時間）**。両方見ると倍の時間がかかるので注意。AIを学習補助に使いたいならChatGPT版、試験範囲に集中したいなら非ChatGPT版を選ぶ。
- 視聴は1.25〜1.5倍速＋**必ずTrailhead Playground（無料の練習環境）で手を動かす**。Adminは操作問題が多く、見るだけでは受からない。
- **Agentforce AI（8%）は講座だけだと手薄になりやすい**ので、Trailheadの該当モジュールで補う。

---

## 全体ロードマップ（13週・3フェーズ）

| フェーズ | 期間 | 内容 |
| --- | --- | --- |
| 1. インプット | W1〜W7（6/15〜8/2） | メイン講座を分野別に視聴＋Playgroundで実習 |
| 2. 演習 | W8〜W11（8/3〜8/30） | NextGen模試4本を周回＋弱点復習＋Agentforce補強 |
| 3. 仕上げ | W12〜W13（8/31〜9/12） | 本番形式の通し模試で安定80%超→受験予約→受験 |

### フェーズ1：インプット（配点比例で配分）

| 週 | 期間 | 学習分野 | 目安 |
| --- | --- | --- | --- |
| W1 | 6/15–6/21 | イントロ＋Configuration & Setup | 講座視聴＋ユーザー/権限をPlaygroundで設定 |
| W2 | 6/22–6/28 | Object Manager & Lightning App Builder | カスタムオブジェクト/項目/ページを自作 |
| W3 | 6/29–7/5 | Sales & Marketing Applications | リード〜商談プロセスを一通り作成 |
| W4 | 7/6–7/12 | Service & Support＋Productivity & Collaboration | ケース/キュー、活動/連携機能 |
| W5 | 7/13–7/19 | **Data & Analytics Management（最重要17%）** | レポート/ダッシュボード/データ品質を重点練習 |
| W6 | 7/20–7/26 | **Automation（Flow中心15%）** | Flow Builderを実際に組む（合否を分ける山場） |
| W7 | 7/27–8/2 | **Agentforce AI（8%）**＋遅れの吸収 | Trailheadで補強。未消化分の挽回バッファ |

### フェーズ2：演習（弱点の特定と潰し込み）

| 週 | 期間 | 内容 |
| --- | --- | --- |
| W8 | 8/3–8/9 | 模試1・2を受験→**間違いを全問解説で復習**→該当分野を講座/Playgroundで再確認 |
| W9 | 8/10–8/16 | 模試3・4を受験→同上。正答率の低い分野をリスト化 |
| W10 | 8/17–8/23 | 弱点分野を集中復習。模試1・2を再受験し改善を確認 |
| W11 | 8/24–8/30 | 模試3・4を再受験。全模試で**安定して70%以上**を目標 |

### フェーズ3：仕上げ（本番化）

| 週 | 期間 | 内容 |
| --- | --- | --- |
| W12 | 8/31–9/6 | 105分の通し模試を本番同様に実施。**80%超**が安定したら受験を予約 |
| W13 | 9/7–9/12 | 苦手項目の最終確認＋誤答ノート総ざらい→**受験**（目安9/12） |

---

## 進め方のルール（デイリー／ウィークリー）
- **デイリー**: 講座 or 模試を1セッション（既存メタタスクの「Salesforce勉強 ×2」を本計画に充当）。視聴した機能は必ずPlaygroundで1回触る。
- **ウィークリー**: 週末にその週の分野を15〜30分で自己テスト（用語を白紙に書き出す）。誤答ノートに追記。
- **誤答ノート**を1ファイル作り、間違えた問題と「なぜ間違えたか」を蓄積する（直前の総復習で最大効果）。

## 合格判定の目安
- フェーズ2終了時（8/30）: 模試で安定70%以上
- フェーズ3（9月上旬）: 通し模試で安定80%以上 → 本番65%に対し十分な余裕

## 残タスク・要確認
- [ ] メイン講座のトラック選択（ChatGPT版／非ChatGPT版）を決める
- [ ] Trailhead Playground（無料）のアカウント準備
- [ ] 受験方法（オンライン監督試験／テストセンター）と受験料を確認し、W12で予約
- [ ] 誤答ノート用のmdファイルを作成

## 履歴
- 2026/06/12: 計画書作成（目標受験日9/12、3教材・13週3フェーズ）
