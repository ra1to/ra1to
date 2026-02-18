## Hi there 👋

**目標**
- インフラ・クラウドの学習
- メモリ効率と堅牢生のある開発

**目的**
- インフラ/Dev・Opsエンジニアになる
---

## 🛠 Technical Skills

- コンテナ: Docker / OrbStack
- IaC: Terraform ※学習中
- OS: Ubuntu, AlmaLinux ※Ubuntuを主に学習中
- CI/CD: GitHub Actions
- インフラ: AWS, GCP

**Frontend**
- 言語: TypeScript
- スタイル: Tailwind CSS
- ライブラリ: TanStack (Query/Router)※学習予定

**Backend**
- 言語: Go※学習中
- データベース:  PostgreSQL, Supabase, CockroachDB※学習中
---

## 🚀 Engineering 

**セルフホスト CI/CD**
サブPCをサーバー（Ubuntu）にして完全自動デプロイ環境を構築を目指している

**流れ**:
- トリガー : GitHub Actionsでテスト・ビルド・Docker HubへのPushを実行
- デプロイ : サーバー側でDocker Hubの更新を検知し、稼働中のコンテナをダウンタイム最小限で最新版へ自動更新
- 次のステップ : k3s × ArgoCDを用いたGitOpsフローへの完全自動化移行も検討中
