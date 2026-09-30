# ユキノシタクリーニング 静的サイト
GitHub Pages で公開できる純粋なHTML/CSSサイトです(ビルド不要)。
- ページ: index(トップ・About統合) / access / price-list / faq / contact
- 文言を直すときは各 .html を直接編集(build.py は初期生成用なので、以後は使わなくて構いません)
- 画像は images/README.md の3枚を配置
- お問い合わせフォーム: contact.html の YOUR_FORM_ID を Formspree(無料枠あり)のIDに置換
## 公開手順
1. GitHubで新規リポジトリを作成し、このフォルダの中身をpush
2. Settings → Pages → Branch: main / (root) を選択
3. 独自ドメインを使う場合は Pages の Custom domain に設定し、ドメイン側のDNSをGitHubに向ける
