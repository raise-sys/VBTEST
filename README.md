## VBの開発をしたいとき(git管理したいとき)

### 構成図
- 12_VB.net
  - 01_xxxx


### 構想
・フォームなどのファイルも管理
・ダウンロードすればすぐ動く状態にしたい
・対象を上書きすればコンパイルできるようにしたい。

1. 12_VB.net をVSCODEでリポジトリの初期化しておく
1. 01_xxxでVBの新規プロジェクトを作成する
2. 上記をコンパイルする
3. 12_VB.net の.ignoreファイルを更新する

## リポジトリ作成(git_Hub上のテスト)
- [GitHub](https://github.com/)にログインして「New」ボタンをクリック
- VBTEST を作成してみる
- CreateRepository
- Quick Setup を取得(https://github.com/raise-sys/VBTEST.git)
- vsCode > 左側GIT のアイコン > ・・・ > リモート > リモートの追加 
   > 上で取得したURLを入力

## リポジトリへのプルとプッシュ
- ・・・ > プル、プッシュ > 指定元からプル
- ・・・ > プッシュ先... > VBTESTを選択

## 新しいフォルダを作成してそこにクローンする(bash)
- フォルダを作成する
- vsCode にて bash を ターミナルのシェルに切り替える
- git clone https://github.com/raise-sys/VBTEST.git

## 新しいフォルダを作成してそこにクローンする(GUI)
- フォルダを作成する
- vsCode にて 左側のアイコンからソース管理を選択
- リポジトリの初期化ボタンをクリック　（使用するフォルダを初期化）
- ... > clone> URL > 上記フォルダを選択
