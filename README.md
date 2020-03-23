# nostring-nosuggest
Googleの検索時に出てくる「検索してみてください」の候補を消すためのChrome拡張機能です

## Usage
大前提として、これはGoogle Chromeの拡張機能であるため利用するためにはGoogle Chromeが必要です。
まず、このリポジトリにあるフォルダを取得してください。
次に、Chromeの「設定」 -> 「拡張機能」で拡張機能の管理画面へと移動します。
次に「デベロッパーモード」をオンにする必要があります。これは、Googleの管理していない拡張機能を実行するためには開発者の状態で実行をしないといけないからです。
そして、一番上にある「パッケージ化されていない拡張機能を読み込む」を選択して、取得したフォルダ(直下に「manifest.json」があるものです)を選択してください。
これによって機能を利用することができます。

## Point
なお、これはあくまで開発者本人の環境でのみ動作することを確認したので、他の環境での動作は補償いたしかねますので、あらかじめご了承ください。