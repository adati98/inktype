INKTYPE Public Beta v4
======================

GitHub Pagesで公開するための構成です。

ファイル
- index.html : サイト本体
- .nojekyll  : GitHub PagesでJekyll処理を無効化する空ファイル

おすすめ公開手順
1. GitHubで新しいPublic repositoryを作成します。
   例: inktype
2. このフォルダ内の index.html と .nojekyll をリポジトリ直下へアップロードします。
3. Repository > Settings > Pages を開きます。
4. Build and deployment の Source で "Deploy from a branch" を選びます。
5. Branch: main / Folder: /(root) を選び Save します。
6. 数分待つと、通常は下記形式で公開されます。
   https://<GitHubユーザー名>.github.io/inktype/

既存サイトがある場合
- <ユーザー名>.github.io というリポジトリが既にあっても、別リポジトリを作れば Project site として追加できます。
- 既存HPのリポジトリを上書きしないでください。

Public Beta v4 の主な機能
- 32問 / 8軸診断
- ブキ種・ルール・ステージ・スペシャルを複数選択
- 各カテゴリ★お気に入り最大3つ
- 12タイプ判定
- v2 / v3 / v4 の結果コード比較
- Xシェアボタン
- Web Share API対応（対応端末）
- 共有文コピー
- プライバシー・免責表記
- フィードバック入力補助
- スマホ向け表示調整

注意
- この版はバックエンドを使用しません。
- 回答や診断結果はサーバーに保存されません。
- Xで共有した場合、共有先には診断文章と公開ページURLのみ渡します。
- 非公式ファンメイドサイトであり、任天堂株式会社その他の権利者とは関係ありません。
