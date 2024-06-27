# Remixメモ
## File Conventions
### Route File Naming
#### Basic Routes
https://remix.run/docs/en/main/file-conventions/routes#basic-routes
- `app/routes`はアプリケーションのルート
- `app/routes/_index.tsx`は`/`で表示されるページ
- `app/routes/about.tsx`は`/about`で表示されるページ
#### Dot Delimiters
https://remix.run/docs/en/main/file-conventions/routes#dot-delimiters
- `.`でurlに`/`が含まれる
#### Dynamic Segments
https://remix.run/docs/en/main/file-conventions/routes#dynamic-segments
- `$`で動的ルーティングを作成できる
- Next.jsの`[]`
#### Nested Routes
https://remix.run/docs/en/main/file-conventions/routes#nested-routes
- 親子関係のあるルーティングを定義する際に使う
- 子のルーティングが親のルーティングのレイアウトを継承する
- 共通レイアウトが必要なケースで有効
- ファイル名を`.`で繋ぐだけ
#### Nested URLs without Layout Nesting
https://remix.run/docs/en/main/file-conventions/routes#nested-urls-without-layout-nesting
- 親子関係のあるルートを定義する際に使う
- 子のルーティングが親のルーティングのレイアウトを継承しない
- 親レイアウトを使用せずに、独立したページとして表示したいケースで有効
- 親ファイルの末尾に`_`をつける
## Route Module
### links
https://remix.run/docs/en/main/route/links
- htmlのlinkタグの機能
- linksで定義した内容が<Links />で読み込まれる

### meta
https://remix.run/docs/en/main/route/meta
- htmlのmetaタグの機能
- titleも定義できる
- metaで定義した内容が<Meta />で読み込まれる

### loader
https://remix.run/docs/en/main/route/loader
- サーバー側でのみ実行されるデータフェッチ
- Next.jsのこれ(https://nextjs.org/docs/app/building-your-application/data-fetching/fetching-caching-and-revalidating#fetching-data-on-the-server-with-fetch)

### action
https://remix.run/docs/en/main/route/action
- サーバー側でのみ実行されるアクションを処理する関数
- GET以外のアクションが呼び出される際に実行される
