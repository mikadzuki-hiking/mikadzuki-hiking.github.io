# 写真の差し替え方

サイトの写真は、すべて `img` フォルダにあります。
**同じファイル名の写真をアップロードすると、そのまま置き換わります**（ページの中身を直す必要はありません）。

## 差し替えの手順（GitHub の画面で。スマホでも可）

1. 差し替えたい写真のファイル名を、下の一覧で確かめる（例：`run.jpg`）
2. 写真のファイル名を**それと同じ名前**にする（英小文字・拡張子は `.jpg`）
   - PC なら `_ツール\写真を縮小.bat` に写真をドラッグ＆ドロップ → 名前を選ぶだけで、
     縮小と名前付けが済みます（`差し替え用写真\` に出来上がる）
3. GitHub で このリポジトリの **`img` フォルダ**を開く
4. 右上の **「Add file」→「Upload files」** → 写真を選ぶ
5. 下の **「Commit changes」** を押す
6. 1〜2 分後にサイトを再読み込み（古い写真が出るときは、もう数分待つか再読み込みをもう一度）

### 気をつけること
- **ファイル名が 1 文字でも違うと置き換わりません**（`Run.jpg`、`run.JPG`、`run.jpeg` は別物扱い）
- **子どもの顔が写った写真は、掲載の許可をもらったものだけ**
- 写真は**縮小してから**上げる（目安：長辺 1200px・500KB 以下。スマホのそのままの写真だと表示が遅くなる）
- スマホの写真をそのまま上げると、**撮影場所（位置情報）が残ることがあります**。縮小ツールを通すと消えます
- iPhone の HEIC 形式（`.heic`）はブラウザで表示できません。JPEG にしてから使う
- 枠は丸みのある形・正方形に切り抜いて表示します。**写したいもの（顔など）は写真の真ん中に**
- 「昨年の様子」は 11 枚で 12 マスを埋めています。**枚数を増やす・減らすときは Claude に頼む**（ページの直しが必要）
- 差し替えたら、次に Claude にサイトを直してもらうとき「GitHub で写真を差し替えた」と一言伝える
  （PC 側の控えを最新にしてから作業するため）

## 写真の場所の一覧

枠の形：■＝正方形、▭＝横長、●＝小さい丸（約 110px）。どの枠も角は丸く切れます。

### 両方のページ

| 写真 | ファイル名 | 出る場所 | 枠 | おすすめ |
|---|---|---|---|---|
| <img src="img/hero.jpg" width="90"> | `hero.jpg` | トップ・2026 の一番上（大きな雲形）。LINE や SNS でサイトを共有したときの画像にもなる | ■ | **縦長**、長辺 1600px。顔はやや右上寄りに |
| <img src="img/view.jpg" width="90"> | `view.jpg` | トップ「なぜ、三日月山ハイキング？」の右／2026「昨年の様子」の先頭（大きい横長） | ▭ | **横長**（4:3 〜 2:1） |
| <img src="img/logo.png" width="60"> | `logo.png` | ロゴ（ページ下・ブラウザのタブ） | ■ | 差し替えるときは Claude に頼む（PNG・透明背景） |

### トップページ「開催までの準備」（6 マス）

| 写真 | ファイル名 | 説明文（写真の下） | 枠 |
|---|---|---|---|
| <img src="img/work-before.jpg" width="90"> | `work-before.jpg` | BEFORE／展望デッキの現地調査 | ■ |
| <img src="img/work-after.jpg" width="90"> | `work-after.jpg` | AFTER／手すりを更新 | ■ |
| <img src="img/work-kusakari.jpg" width="90"> | `work-kusakari.jpg` | 登山道の草刈り | ■ |
| <img src="img/work-cut.jpg" width="90"> | `work-cut.jpg` | 部材の加工 | ■ |
| <img src="img/work-post.jpg" width="90"> | `work-post.jpg` | 支柱の建て込み | ■ |
| <img src="img/work-rail.jpg" width="90"> | `work-rail.jpg` | 展望デッキの仕上げ | ■ |

### 2026 ページ「プログラム」（小さい丸）

| 写真 | ファイル名 | 横の見出し | 枠 |
|---|---|---|---|
| <img src="img/stamp.jpg" width="90"> | `stamp.jpg` | フォトスタンプラリー | ● |
| <img src="img/zipline.jpg" width="90"> | `zipline.jpg` | 巨大ブランコ ＆ ジップライン | ● |
| <img src="img/kite.jpg" width="90"> | `kite.jpg` | ワークショップ | ● |
| <img src="img/nabe.jpg" width="90"> | `nabe.jpg` | ふるまいコーヒー ＆ あったかドリンク | ● |

### 2026 ページ「昨年の様子」（先頭の `view.jpg` ＋ 下の 10 枚）

| 写真 | ファイル名 | 説明文（写真の下） | 枠 |
|---|---|---|---|
| <img src="img/kataguruma.jpg" width="90"> | `kataguruma.jpg` | 肩車で絶景 | ■ |
| <img src="img/deck.jpg" width="90"> | `deck.jpg` | 展望台 | ■ |
| <img src="img/swing.jpg" width="90"> | `swing.jpg` | 巨大ブランコ | ■ |
| <img src="img/zipline2.jpg" width="90"> | `zipline2.jpg` | ジップライン | ■ |
| <img src="img/run.jpg" width="90"> | `run.jpg` | 山道をハイキング | ■ |
| <img src="img/walk.jpg" width="90"> | `walk.jpg` | 森の道 | ■ |
| <img src="img/kite2.jpg" width="90"> | `kite2.jpg` | 凧揚げ | ■ |
| <img src="img/plate.jpg" width="90"> | `plate.jpg` | 皿回し | ■ |
| <img src="img/ginkgo.jpg" width="90"> | `ginkgo.jpg` | いちょう並木 | ■ |
| <img src="img/drink.jpg" width="90"> | `drink.jpg` | ふるまいコーヒー | ■ |

- 写真の下の**説明文**や、**写真の説明（画面の読み上げ用）**を変えたいときは Claude に頼む
  （写真だけ替えて内容が変わる場合は、説明文も合わせて直す）

### いまはどこにも使っていない写真

`deck2.jpg`・`forest.jpg`・`group.jpg`・`kataguruma2.jpg`・`plaza.jpg`・`smile.jpg`・`work-deck.jpg`・`insta-qr.png`・`map-qr.png`
（以前の候補。これを上書きしてもサイトは変わりません）
