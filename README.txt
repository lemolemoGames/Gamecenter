GameCenter 初期セット

1. このZIPを展開します。
2. 中の GameCenter フォルダの内容を、作成済みの GameCenter フォルダへコピー（上書き）します。
3. index.html をダブルクリックしても一覧画面の見た目は確認できますが、Service Worker とオフライン機能は localhost または HTTPS 上でのみ動きます。
4. 次の段階でローカルサーバーを起動してPCのChromeで動作確認し、その後無料ホスティングへ配置します。

ゲーム追加時は games 内にゲーム用フォルダを作り、index.html の data-game ボタンと service-worker.js の APP_FILES に追加します。
