# GitHub運用ポリシー（技術コミュニティ）

---

### リポジトリ構成ルール

| 命名規則 | 説明 | アクセス範囲 |
| --- | --- | --- |
| `Home` | コミュニティ共通の運営情報・ガイドラインを集約 | 全世界 |
| `pj-xxxx` | 検証・実験・PoC単位のテーマごとに作成。原則非公開だが、PJ内で合意が取れたものから順次knowledges等に公開 | ITDTメンバ限り |
| `knowledges`  | 技術的なナレッジを蓄積。Sovityワークショップ等のドキュメント・コンテンツもここにおく | ITDTメンバ限り |

---

### Issue / Discussion / PR の使い分け

| 機能 | 目的 |
| --- | --- |
| Issues | タスク管理、バグ報告、明確な提案など（ToDo） |
| Discussions | 雑談・相談・方向性検討・共有・アイデア出しなど |
| Pull Requests | ドキュメントやコードの変更提案。原則Issueに紐づけ |

---

### Homeリポジトリの構成案

- README.md
- [github-guide.md]() ：GitHub Orgの使い方（本ドキュメント）
- guidelines
    - public-private-policy.md: 社内資料含め、資材のアクセス範囲を記したガイドライン
 
---
### knowledgesリポジトリの構成案
- onboarding　
    - [https://github.com/UTokyo-ITDT/knowledges/blob/main/onboarding/index.md]()：オンボーディングの目次
    - [https://github.com/UTokyo-ITDT/knowledges/blob/main/onboarding/edc-setup.md]()：EDC環境の構築方法
    - [https://github.com/UTokyo-ITDT/knowledges/blob/main/onboarding/cadde-setup.md]()：DATA-EX環境の構築方法
    - [https://github.com/UTokyo-ITDT/knowledges/blob/main/onboarding/vpn-setup.md]：VPN網への参加方法
