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
- 

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
