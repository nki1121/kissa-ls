# ☕️kissa-ls
後ほどバッジを記載する。
lsコマンドの再開発、喫茶店のメニュー表のようなUIで情報を表示する。

# ✏️Description
lsコマンドを再開発したものである。

# 💡Usage

基本的には標準的な `ls` コマンドと同じ感覚で使用できます。

### 基本的な使い方
```bash
# カレントディレクトリのファイルを表示
$ kissa-ls

# 特定のディレクトリを指定
$ kissa-ls src/

# 詳細表示（サイズ可視化、README tagline、PDFタイトルなど）
$ kissa-ls -l

# カフェメニュー風のUIで表示
$ kissa-ls -menu

# 24時間以内の新着ファイルに 🆕 を付け、ファイルサイズ順にソート
$ kissa-ls -new -sort size

# ignore設定を反映させつつ、詳細表示
$ kissa-ls -l -ignore
```