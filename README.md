# note-example

AIエージェント（Claude）に任せて作ったサイトの見本です。内容（店名、人物、住所、電話番号など）はすべて架空です。

- 公開ページ: https://solt310.github.io/note-example/

| フォルダ | 内容 | 見本 |
|---|---|---|
| [guide/](guide/) | この仕組みの紹介ページ（LP）「AIに頼むホームページ」 | https://solt310.github.io/note-example/guide/ |
| [shop/](shop/) | 1ページのサイト（HTML / CSS / JavaScript）。架空のパン屋「こむぎの森」 | https://solt310.github.io/note-example/shop/ |
| [corporate/](corporate/) | お知らせのある複数ページのサイト（Astro）。架空の会計事務所「みどり会計事務所」 | https://solt310.github.io/note-example/corporate/ |
| [media/](media/) | ウェブマガジン（EmDash）。架空の港町の「まちあるき日和」 | https://solt310.github.io/note-example/media/ |

各フォルダには、ビルド済みの公開用ファイルだけを置いています。本来は Cloudflare Workers でドメイン直下に公開する構成のため、このリポジトリでは URL とパスを `/note-example/<フォルダ>/` に書き換えています。

旧フォルダ名（html/・astro/・emdash/）の URL は、トップの `404.html` が新しいフォルダ（shop/・corporate/・media/）の同じページへ転送します。
