# C言語の開発環境設定  
## Windowsの場合  
windowsの場合は`minGW`というものがあります。まだ開発環境が整っていない人はこちらを参照して見てください。  
### MinGWのインストール  
1. こちらのリンクをクリックしてインストーラーをダウンロードする。
![image7](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image07.png "image07")  
2. ダウンロードしたインストーラーを起動して`install`をする。  
![image8](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image08.png "image08")  
3. 次にインストールをする際の設定をします。  
・`Installation Directory`（インストール先のフォルダ）  
・`User Interface Options`（ユーザーインターフェイスの設定）  
![image9](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image09.png "image09")  
4. `Continue`をクリック  
![image10](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image10.png "image10")  
5. すると`MinGW`インストールが始まります。  
![image11](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image11.png "image11")  
6. １００％になったらインストール完了です。  
![image12](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image12.png "image12")  
7. インストール先にインストールが完了していると思います。それを起動させます。  
![image13](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image13.png "image13")  
8. チェックボックスがあると思います。そこの`mingw32-base`を右クリックして`Mark for Installation`をクリック。  
![image14](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image14.png "image14")  
![image15](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image15.png "image15")  
9. 次に、２つのチェックボックスにチェックをつけます。  
・`mingw32-base`  
・`mingw32-gcc-g++`  
![image16](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image16.png "image16")  
10. 上のメニューから`Installtion`から`Apply Changes`を選択する。  
![image17](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image17.png "image17")  
11. クリックすると、`Schedule of Pending Actions`というウィンドウが出てくるので、`Apply`をクリックする。  
![image18](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image18.png "image18")  
12. クリックするとパッケージのインストールが始まります。完了したら`Close`を押して完了です。  
![image19](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image19.png "image19")  
### パスを通す  
パスを通します。  
1. コントロールパネルを起動する。 
![image20](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image20.png "image20")  
2. システムとセキュリティをクリックします。  
![image21](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image21.png "image21")  
3. システムをクリックします。  
![image22](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image22.png "image22")  
4. 左のシステムの詳細をクリック  
![image23](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image23.png "image23")  
5. クリックすると、システムのプロパティが表示されるので、環境変数をクリックする。  
![image24](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image24.png "image24")  
6. 環境変数です。システムの環境変数にあるPashを選択して編集をクリックすます。  
![image25](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image25.png "image25")  
7. 変数値末尾に次のパスを追加してOKをクリックします。  
`;C:¥MinGW¥bin`  
![image26](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image26.png "image26")  
8. OKをクリックします。  
![image27](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image27.png "image27")  
9. コマンドプロンプトを起動して、次のコマンドを実行して見ましょう。  
![image28](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image28.png "image28")  
10. `gcc --version`   
11. このように表示されているか確認して完了になります。  
![image29](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image29.png "image29")  
```
> gcc --version  
gcc (GCC) 4.8.1  
Copyright (C) 2013 Free Software Foundation, Inc.  
This is free software; see the source for copying conditions.  There is NO  
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  
```
  
## macの場合  
- xcodeをインストールする時にcommandlinetoolsをインストールしたと思います。それがあるとターミナルでコマンドを打つことができます。  
これを使ってもオーケーです。  
その際に使うエディターは好みのものを使うといいと思います。例えば、Visual Studio CodeとかCotEditorとかAtomとかですかね。ちなみに僕はsublimeを使っています。参考までに載せておくのでよければ使って見てください。エディターにこだわりがなければターミナルから`vi hogehoge.c`で書くこともできます。  
- Atom https://atom.io/  
- sublime https://www.sublimetext.com/  
- visual studio code https://www.visualstudio.com/products/free-developer-offers-vs.aspx  
- CotEditor https://coteditor.com/  
- mi http://www.mimikaki.net/  
また、IDEAを使いたい人は、こちらにリンクをはっつけておきます。かなり重たいので、参考までに。  
- xcode https://itunes.apple.com/jp/app/xcode/id497799835?mt=12  
- eclips http://www.eclipse.org/  
- CLion https://www.jetbrains.com/clion/  
以上で完了です。  
[戻る](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/,jdk_12_install.md)
