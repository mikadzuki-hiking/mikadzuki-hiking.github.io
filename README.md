# 三日月山ファミリーハイキング 2026 紹介サイト

公開 URL：**https://mikadzuki-hiking.github.io/**
（GitHub Pages。リポジトリ `mikadzuki-hiking/mikadzuki-hiking.github.io`、`main` ブランチ直下を公開）

## ファイル
| ファイル | 内容 |
|---|---|
| `index.html` | サイト本体（1 ページ・CSS 込み・外部ライブラリなし。Google Fonts の Zen Maru Gothic / Poppins のみ） |
| `img\` | Web 用に縮小した写真（元は `..\素材\`。英字ファイル名）とロゴ |
| `QR_サイト_印刷用.png` | サイト URL の QR（濃紺・余白付き、チラシ・ポスター用） |
| `QR_サイト_SNS用.png` | Instagram 投稿・ストーリー用の QR 画像（1080×1080） |
| `.nojekyll` | GitHub Pages の変換処理を止める印（消さない） |

## 更新の仕方（Claude Code に頼むとき）
1. `index.html` を直す（文言・写真）。写真を足すときは `..\素材\` から縮小して `img\` に英字名で置く
2. ブラウザで見た目を確認（スマホ幅も）
3. このフォルダで `git add -A` → `git commit -m "…"` → `git push origin main`
4. 1〜2 分で公開に反映される（`https://mikadzuki-hiking.github.io/` を再読み込み）

## 決まりごと
- 文言・数値はチラシ案C2 と一致させる（どちらかを直したらもう一方も）
- 参加者の顔が写る写真は掲載許可を確認したものだけ使う
- 日程・参加費などの「仮」の情報は `..\README.md` の「未確定・要確認」を正とする
