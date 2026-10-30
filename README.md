# note-example

AIエージェント（Claude）に任せて作ったサイトの見本です。内容（店名、人物、住所、電話番号など）はすべて架空です。

- 公開ページ: https://solt310.github.io/note-example/

| フォルダ | 内容 | 見本 |
|---|---|---|
| [html/](html/) | 1ページのサイト（HTML / CSS / JavaScript）。架空のパン屋「こむぎの森」 | https://solt310.github.io/note-example/html/ |
| [astro/](astro/) | お知らせのある複数ページのサイト（Astro）。架空の会計事務所「みどり会計事務所」 | https://solt310.github.io/note-example/astro/ |
| [emdash/](emdash/) | ウェブマガジン（EmDash）。架空の港町の「まちあるき日和」 | https://solt310.github.io/note-example/emdash/ |

各フォルダには、ビルド済みの公開用ファイルだけを置いています。本来は Cloudflare Workers でドメイン直下に公開する構成のため、このリポジトリでは URL とパスを `/note-example/<フォルダ>/` に書き換えています。
