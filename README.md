## Hi there 👋

---

## 🛠 Technical Skills

**Infrastructure & DevOps (Core Focus)**
- コンテナ: OrbStack
- IaC: Terraform※学習中
- CI/CD: GitHub Actions, self-host on Ubuntu, Watchtower
- Cloud/Server: AWS, Home Server (Ubuntu)　※どちらも学習中

**Frontend**
- Languages: React , TypeScript
- Styling: Tailwind CSS
- Libraries: TanStack (Query/Router)※学習中

**Backend**
- Languages: Go※学習中
- Database:  PostgreSQL, CockroachDB,　Supabase

---

## 🚀 Engineering 

**セルフホスト CI/CD**
サブPCをサーバー（Ubuntu）にして完全自動デプロイ環境を構築を目指している

**流れ**:
- Trigger: GitHubへのPushを検知し、GitHub Actionsでテスト・ビルド・Docker HubへのPushを実行
- Deploy: サーバー側のWatchtowerがDocker Hubの更新を検知し、稼働中のコンテナをダウンタイム最小限で最新版へ自動置換
- Next Step: k3s × ArgoCDを用いたGitOpsフローへの完全自動化移行も検討中

**目的**:
開発サイクルの高速化と実務環境に近いインフラ運用の実践を学習中

---
