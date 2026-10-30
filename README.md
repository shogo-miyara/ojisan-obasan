# おじさん★おばさん SLOT — GitHub Pages 配布版

## 内容
- `index.html` — スロットゲーム本体。**v15に収録されていた画像を削らずそのまま保持**している。
- `assets/ojisan_obasan_bonus.mp3` — 提供された音源（原本のまま）。おじさんBONUS／おばさんBONUSのBGM。ボーナス終了時に停止し、ループ再生する。
- `.nojekyll` — GitHub Pages用
- `ASSET_MANIFEST.txt` — 収録画像の内訳

ボーナス中、収録した旅行写真を約2.5秒ごとに順送りする。音楽の再生がスマホに制限された場合はボーナス画面の「♪ 音楽を再生」をタップ。

## GitHub Pages で公開
1. このZIPを解凍する。
2. GitHubで新しいリポジトリを作成する。
3. `index.html`、`assets` フォルダー、`.nojekyll` 等をリポジトリの**最上位**にアップロードする。**ZIPファイルだけアップロードしても公開されない**。
4. Settings → Pages → Build and deployment → Deploy from a branch を選択。
5. main ブランチ、/(root) を選んで保存。表示された公開URLを開く。

## 注意
写真に写る人物の公開許可と、楽曲の著作権・公開配布権利を確認すること。GitHub Pagesでの配布はインターネット上の一般公開となる。
