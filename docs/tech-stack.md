# 技術選定memo 

## 開発環境: Docker
 - サーバサイド: Ruby on Rails 7系
　　Ruby 3.2.2 Rails 7.0.4.3
 - フロントエンド: HotWire
-  CSSフレームワーク: bootstrap5系、Silicon（Bootstrapテンプレート）
-  WebAPI: Google Maps API（GoogleマップのジオロケーションAPI）、 Amazon Rekognition（画像解析サービス）
-  インフラ:
 -  Webアプリケーションサーバ: Fly.io
 - ファイルサーバ: AWS S3
 - セッションサーバ: Redis（Redis by Upstash）
 - データベースサーバ: PostgreSQL（Fly Postgres）
## その他：
 - VCS: GitHub
 - CI/CD: GitHubActions
 