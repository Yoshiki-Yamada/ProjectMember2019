# Homebrweのインストール  
1. まず、Homebrewをインストールします。こちらにアクセスしてターミナルにコマンドをコピーペーストしてください。  
[homebrewのリンク](https://brew.sh/index_ja)  
![image05](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image05.png "image05")  
すると、Homebrewのインストールが始まります。時間がかかる場合もあります。  
- 途中でエンターの入力やmacのpassの入力を求められることがあります。  
passを打つときは何も表示されないので、気をつけて作業してください。  
```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

（中略）

Press RETURN to continue or any other key to abort
==>

(中略)

Password:

(中略)

==> Installation successful!

==> Homebrew has enabled anonymous aggregate user behaviour analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics.html

==> Next steps:
- Run `brew help` to get started
- Further documentation:
    https://docs.brew.sh
  ```  
これでインストールが完了しました。ターミナルに`brew -v`と打って確認して見ましょう。  
結果
```
Homebrew 2.1.16
Homebrew/homebrew-core (git revision 7e82b; last commit 2019-11-10)
Homebrew/homebrew-cask (git revision cdb90; last commit 2019-11-11)
```
