## Hi there 👋

---

## 🛠 Technical Skills

**Infrastructure & DevOps (Core Focus)**
- コンテナ: Docker
- IaC: Terraform
- CI/CD: GitHub Actions, self-host on Ubuntu, Watchtower
- Cloud/Server: AWS, Home Server (Ubuntu)

**Backend**
- Languages: Node.js(TypeScript), Go
- Database: CockroachDB, PostgreSQL, Supabase

**Frontend**
- Stack: React , TypeScript
- Styling: Tailwind CSS
- Libraries: TanStack (Query/Router)

---

## 🚀 Engineering 

**セルフホスト CI/CD**
サブPCをサーバー（Ubuntu）にして完全自動デプロイ環境を構築・運用中

**流れ**:
- Trigger: GitHubへのPushを検知し、GitHub Actionsでテスト・ビルド・Docker HubへのPushを実行
- Deploy: サーバー側のWatchtowerがレジストリの更新を検知し、稼働中のコンテナをダウンタイム最小限で最新版へ自動置換
- Next Step: k3s × ArgoCDを用いたGitOpsフローへの移行検証も進行中

**目的**:
開発サイクルの高速化と実務環境に近いインフラ運用の実践を学習中

---
