<img width="1131" alt="スクリーンショット 2024-11-14 2 27 30" src="https://github.com/user-attachments/assets/97f5c936-d65c-4a91-968e-ac95697c17c2" />

# イベント掲載アプリ

## 概要

このプロジェクトでは、connpass のような、イベントの掲載・申し込みができるアプリを構築します。
クライアントサイドルーティングを実践し、SPA（シングルページアプリケーション）を開発します。

## 学習目標

React Router による、クライアントサイドルーティングの基本を学習します。

- React Router による基本的なルーティング
- 動的な値に応じたルーティング
- 存在しない URL の処理
- リダイレクトの処理
- ネストしたルーティング
- 複数ページでのレイアウトの共通化

### 推奨技術

このプロジェクトの難易度と趣旨を踏まえて、以下の使用をお勧めします。

- React Router によるルーティングの実装
- vite を用いた React 環境構築
- Tailwind CSS を用いたスタイリング
- TypeScriptによる型チェック
- vercel へのデプロイ

---

## 🎯 お題

- 「ユーザーストーリー」を全て満たす、アプリを構築してください。
- 必要に応じて、スクリーンショットやデモサイトの URL を、参照してください。
- なお、スタイルは、あなた自身で独自にカスタマイズすることが可能です。
- イベントのデータに関しては、ダミーのデータで構いません。
- メールアドレスを用いた申し込み機能は、実装しなくても構いません。

### 必須機能

このアプリは、以下の 4 つのページで構成されています：

1. **イベント一覧ページ**：
   - サイトアクセス時に、イベント一覧を表示する。
2. **イベント詳細ページ**：
   - イベント詳細情報を表示する。
3. **イベント申し込みページ**：
   - イベントに申し込むためのメールフォームを表示する。
4. **申し込み完了ページ**：
   - 申し込み完了メッセージを表示する。

## ユーザーストーリー

- **TOP ページ:**
  - [ ] ユーザーがサイトにアクセスすると、開催予定のイベント一覧を閲覧できる
  - [ ] 個別のイベントをクリックして、詳細ページに遷移できる
- **イベント詳細ページ**:
  - [ ] ユーザーは各イベントの詳細情報を確認できる
  - [ ] 参加希望者向けの、し込みボタンをクリックして、申し込みページに遷移できる
- **イベント申し込みページ**:
  - [ ] ユーザーは参加要件の最終確認ができる
  - [ ] 「_申し込みを確定する_」ボタンをクリックして、申し込みを完了できる
- **申し込み完了ページ**:
  - [ ] ユーザーはイベントへの申し込み完了を確認できる
  - [ ] 完了ページには、TOP ページへの URL リンクが配置されている
- **その他**：
  - [ ] フッターとヘッダーが、全ページ共通のレイアウトとして表示されている
  - [ ] アプリケーションがデプロイされており、誰でもアクセス可能である。
  - [ ] クライアントサイドルーティング（SPA）が実装されている
