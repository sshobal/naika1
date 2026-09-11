内科1 Practice Lab v6.6 — GitHub Pages そのままアップロード版

このZIPは、解凍後に中のファイルをそのままGitHubへアップロードできるように整理してあります。
「web」フォルダへ移動したり、ファイルを並べ替えたりする必要はありません。

【GitHub Pages 公開手順】
1. このZIPをWindowsで解凍する。
2. GitHub (https://github.com/) にログインする。
3. 右上の + → New repository を選ぶ。
4. Repository name に、例として naika1-practice と入力する。
5. Public を選択して Create repository を押す。
6. 作成したRepositoryで「uploading an existing file」を選ぶ。
7. このフォルダ内の以下の6ファイルをすべてドラッグ＆ドロップする。
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - icon-192.png
   - icon-512.png
   - .nojekyll
   ※ README_最初に読んでください.txt はアップロードしてもしなくても構いません。
8. Commit changes を押す。
9. Repository上部の Settings → 左側 Pages を開く。
10. Build and deployment の Source を「Deploy from a branch」にする。
11. Branch を「main」、Folder を「/ (root)」にして Save。
12. 数分待つ。
13. Pages画面に表示される「Your site is live at ...」のURLをAndroidのChromeで開く。

【Androidにアプリとして入れる】
1. AndroidのChromeで上記URLを開く。
2. ページが完全に表示されるまで一度待つ。
3. Chrome右上の︙をタップ。
4. 「アプリをインストール」または「ホーム画面に追加」を選ぶ。
5. ホーム画面にできた「内科1 Practice」アイコンから起動する。

【オフライン利用】
最初の1回だけ、GitHub Pages上で全体を読み込んでください。
その後はService Workerのキャッシュにより、ネット接続がない状態でも起動できる構成です。

【進捗について】
進捗は端末内に保存されます。通常、アプリを閉じても残ります。
ただし、Chromeの「サイトデータを削除」、アプリのストレージ消去、PWAの削除をすると消える可能性があります。
定期的にPractice Lab内の「進捗を書き出す」でバックアップしてください。

【更新するとき】
新しい版をGitHubへアップロードしてCommitすると、次回オンライン起動時に更新できます。
古い表示が残る場合は、アプリを完全に閉じて再度開いてください。
