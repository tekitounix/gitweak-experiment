# Gitweak 実験用アカウント

これは [Gitweak](https://github.com/tekitounix) の設計検証用の**実験リポジトリ**です。
1 つの公開リポジトリ = 1 つの Gitweak アカウント（`gitweak.json` がマニフェスト）。

- `gitweak.json` … アカウントマニフェスト（DID・公開鍵・**配置先に署名で束縛**）
- `posts/…/post.json` … 署名付き投稿
- `index/latest.json` … タイムライン索引

秘密鍵はこのリポジトリには含まれません（公開情報のみ）。
Account DID: `did:key:z6MkknoLrXAtHKkKJaRCXEeY6Rv6ShMsBxQy6UHQkocovu7C`
