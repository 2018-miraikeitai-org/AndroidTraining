# AndroidTraining

Android学習用リポジトリです

## 準備

1. AndroidStudioの導入

Android開発ではAndroidStudioというソフトウェアを使用します。
[AndroidStudioダウンロードページ](https://developer.android.com/studio/)からAndroidStudioをダウンロードしインストールしましょう。

2. gitの導入

開発にはgitを使用します。[このページ](https://eng-entrance.com/git-install)などを参考にgitを利用できる環境を作りましょう。

## 事前知識

この課題ではgit, githubを使用します。勉強しましょう。

### 資料

- [サルでもわかるGit入門](https://backlog.com/ja/git-tutorial/intro/intro1_1.html)
- [【GitHub超初心者入門】この前初めてGitHubを使い始めたエンジニア見習いが書くGitHubの使い方と実践～とりあえず一緒に動かしてみようぜ！～](https://qiita.com/nnahito/items/565f8755e70c51532459)

## 課題の流れ

1. このリポジトリをcloneします
2. 自分の名前のブランチを切ります(ex. `git checkout -b takahashi`)
3. リポジトリのルートに自分の名前のディレクトリを作成します(ex. `mkdir ~/AndroidTraining/takahashi`)
4. 作成したディレクトリの中にAndroidのアプリを作成します
5. 指定された課題が完了したところでリモートの自分の名前のブランチにプッシュします(ex. `git push origin takahashi`)
6. masterにプルリクエストを作成します
7. レビューをもらいmasterにマージされたところで課題完了です

## 課題

### 1.　エミュレータの起動

AndroidStudioの起動後、エミュレータを起動してHelloWorldと表示されるアプリが起動されることを確認しましょう

### 2. ビューの追加

画面に任意の文字列を表示してみましょう

### 3. リストビューの表示（難）

リストを表示してみましょう

ここまでできたらリモートにプッシュしましょう