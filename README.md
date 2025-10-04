# Memscent Mockups

MemscentプロジェクトのHTMLモックアップ開発リポジトリです。

## 🌐 GitHub Pagesで公開中
このプロジェクトはGitHub Pagesで公開されています。

## ✨ 機能
- レスポンシブデザイン対応のHTMLモックアップ
- 香水レビューサイトのUI/UXプロトタイプ
- 8つの主要ページ構成

## 📄 ページ一覧
- **メインページ** (`index.html`) - サイトのホームページ
- **ログイン** (`login.html`) - ユーザーログインページ
- **ユーザー登録** (`register.html`) - 新規アカウント作成
- **香水詳細** (`perfume-detail.html`) - 個別香水の詳細情報
- **香水登録** (`perfume-register.html`) - 新しい香水の登録
- **レビュー投稿** (`review-post.html`) - レビュー作成・投稿
- **検索結果** (`search-results.html`) - 香水検索結果表示
- **ユーザープロフィール** (`user-profile.html`) - ユーザー情報管理

## 🚀 GitHub Pagesでの公開方法

### 1. リポジトリをGitHubにプッシュ
```bash
git remote add origin [YOUR_GITHUB_REPOSITORY_URL]
git push -u origin main
```

### 2. GitHub Pages設定
1. GitHubリポジトリの「Settings」タブに移動
2. 左サイドバーの「Pages」をクリック
3. 「Source」で「Deploy from a branch」を選択
4. 「Branch」で「main」を選択
5. 「Save」をクリック

### 3. 自動デプロイ
- `.github/workflows/pages.yml`により、`main`ブランチへのプッシュで自動デプロイされます

## 🛠 ローカル開発
```bash
# リポジトリをクローン
git clone [YOUR_GITHUB_REPOSITORY_URL]
cd Memscent-mockups

# ローカルサーバーで確認（オプション）
python3 -m http.server 8000
# または
npx http-server
```

## 📱 レスポンシブ対応
全ページでモバイル・タブレット・デスクトップに対応したレスポンシブデザインを実装しています。

## 🔄 更新履歴
- 初回リリース: HTMLモックアップの基本構成
- GitHub Pages対応: 自動デプロイ設定追加