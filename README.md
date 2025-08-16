# 影と光（拡大ボード＋移動アニメ）PWA 一式

## 置き方（GitHub Pages）
1. このフォルダ内のファイルをリポジトリ直下へ配置（`main`ブランチ推奨）。
2. リポジトリ Settings → Pages で `Deploy from a branch / main / /(root)` を選択。
3. 公開URLを開く（例: `https://<USER>.github.io/<REPO>/index.html?v=1`）。
4. Androidは「ホーム画面に追加」でPWA化できます。iOSはSafariの共有→ホームに追加。

## 切り分け
- まず `index_no_pwa.html` が表示されるか確認（PWA無効）。
- 真っ白になる時は、ブラウザのサイト設定→ストレージ→**クリア＆リセット**後に再アクセス。
