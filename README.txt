Mots & Words / 個人用フランス語・英語単語メモ PWA

ファイル:
- index.html: アプリ本体
- manifest.webmanifest: ホーム画面用設定
- sw.js: オフライン動作用
- icon.svg: アプリアイコン

公開方法:
1. GitHubで新規の公開リポジトリを作成
2. このフォルダの4ファイル（README.txt以外）をリポジトリ直下へアップロード
3. Settings > Pages > Build and deployment で Deploy from a branch、main、/(root) を指定
4. 表示された https://ユーザー名.github.io/リポジトリ名/ をiPhoneのSafariで開く
5. 共有メニュー > ホーム画面に追加

注意:
- GitHub Pagesの公開リポジトリはアプリのソースコードが公開されます。単語データはGitHubにアップロードされません。
- IndexedDBのデータはブラウザ内に保存され、バックアップは設定タブから手動で作成します。
- iPhoneのSafariで動作確認を行ってください。端末固有の挙動は未検証です。
