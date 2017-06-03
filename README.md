- [シビライザー英語版公式ページ](http://suewonjp.github.io/civilizer/)
- [シビライザー英語版Githubページ](https://github.com/suewonjp/civilizer)
- [シビライザーSourceforgeページ](https://sourceforge.net/projects/civilizer/)
- [シビライザーツイッター @civilizer_pkm](https://twitter.com/civilizer_pkm)
- [シビライザーチュートリアルビデオ](https://www.youtube.com/watch?v=0omObKmJd4E&feature=youtu.be)
- [シビライザー英語版ドキュメント](https://github.com/suewonjp/civilizer/wiki)
- [機能要求＆バグ報告＆ヘルプなど（英語）](https://github.com/suewonjp/civilizer/issues)
- [シビライザー日本語版Githubページ](https://github.com/suewonjp/civilizer-jpdoc)
- [シビライザー日本語版ドキュメント](https://github.com/suewonjp/civilizer-jpdoc/wiki)
- [機能要求＆バグ報告＆ヘルプなど（日本語）](https://github.com/suewonjp/civilizer-jpdoc/issues)

### :coffee: 始めに

**シビライザー**は主に**ノートやメモ書きおよび個人知識管理**の目的に使えるアプリケーションであり次のようなものを管理・検索出来ます．

- 職業における（専門）知識
- 一時的なメモやノート
- スケジュール & プラン & やることリスト（todo list）
- 覚え難い詳細な段取り
- 表現や単語 (外国語を学ぶ時など)
- アイディア/インスピレーション
- 格言やことわざ，ユモーア
- その他，後でアクセスしそうな様々な知識や情報 

シビライザーはエバーノートのようなノート書きアプリケーションですが，  
デスクトップ専用アプリケーションと異なって, ブラウザー上で動くことでもっとウェブ環境にやさしいです．  

### :coffee: ディスカッション
シビライザーは次のようなデータ形式を管理出来ます．

- テキスト
    - [マークダウン](https://ja.wikipedia.org/wiki/Markdown) で作成・編集
    - 最終的にHTMLとして表示
- リンク
- 画像
- ビデオ
- ファイル

そして次のような方法で効率的にデータ管理を行えます:

- データへのタグ付け
- 類似的／対照的なデータ同士の紐付け
- 頻繁にアクセスするデータへのブックマーク
- ファイルをディレクトリ構造で階層的に管理

シビライザーは**効率的なフールテキスト検索機能**を用いて探したいデータを素早くユーザーに提供します．

**[ スクリーンショット ](http://suewonjp.github.io/civilizer/#screenshots)や[チュートリアルビデオ](http://suewonjp.github.io/civilizer/#videos)** をご覧ください．

* * *

### :coffee: 事前に必要なもの

Java ランタイム環境 (JRE)

- JRE 7以上

支援するプラットフォーム:

- Linux
- OS X（マック）
    - Mavericks あるいはその以降のバージョン
- Windows
    - 7/8/10 あるいはその以降のバージョン

支援するブラウザー: 

- Firefox
- Safari
- Chrome
- Opera
- Edge
- Internet Explorer
    - 9/10/11 ( ９／１０はレイアウトやスタイルなど一部問題あり )
    
### :coffee: インストール／実行
    
1. **JRE (バージョン 7+)がインストールされているのか確認してください．**
    - `java -version` をコマンドライン（コマンドプロンプト）から実行して確認しましょう.
1. シビライザーの[最新バージョン](http://suewonjp.github.io/civilizer/#services) をダウンロードして解凍します．
1. 次のような方法で実行します.
    - Windowsユーザー:
        - `civilizer-win32.exe` を実行
        - あるいは `run-civilizer.bat` をコマンドラインから実行
    - その他のOSユーザー:
        - `run-civilizer.sh` をコマンドラインから実行
1. **システムトレイアイコン** が表示されます． （**Linuxでは表示されません**）
    - アイコンはロードが完全に終了するまで赤色のままです.
    - ロードは多少時間がかかりますのでお待ちください.
    - ロードが終わったらアイコンの色が変更されシビライザーをブラウザー上でアクセス出来ます．
1. シビライザーをアクセスします. 
    - ここまで順調であればブラウザーが自動的に立ち上がります.
    - ブラウザーが反応しない場合は手動でアクセスします.
        - シビライザーのシステムトレイアイコンを右クリックし(OSによっては左クリック)`Browse`と書かれたメニューを選択します．
        - あるいは次のURLをブラウザーのアドレスバーに入力しアクセスします．
            - `http://localhost:8080/civilizer/app/home`
1. シビライザーを最初に起動する際には認証ページが開かれます.
    - 初期のユーザー名とパスワードはこちら:
        - _ユーザー名:owner_
        - _パスワード:owner_
    - 認証後, アプリケーションページが開かれます.
        - 現在，メニュー環境の初期設定は英語になっています．日本語メニューに変更します．
            - ページの右上のコーナーにあるユーザープールダウンメニュー（人アイコン）をアクセスしてください. 
            - `Change Locale` メニューを選択　＞　`日本語`を選択　＞　`OK`ボタンを押す　＞　日本語メニューに切り替わる
        - さらに同じユーザープルーダウンメニューの`プロファイルの変更` メニューからユーザー名とパスワードを変更してください.
        
        
> **日本語メニュー環境に切り替える別の方法**
>
> シビライザーを１回実行しますとユーザーホームディレクトリに`.civilizer`という名前のフォルダーが作られます．
> そのフォルダーにある`app-options.properties`というファイルをメモ帳などで開きましょう．
> 次の行をそのファイルへ追加し保存します．
>> civilizer.locale=ja
>
> シビライザーを１回シャットダウンし再起動します．
     
### :coffee: アンインストール

1. 解凍したディレクトリを削除してください．
1. ユーザーホームディレクトリにある `.civilizer` フォルダーを削除してください.
   
### :coffee: ビルド方法

[このページ](https://github.com/suewonjp/civilizer-jpdoc/wiki/ビルド)を参照してください．

* * *
### :coffee: クレジット 

シビライザーは森田大輔さんが開発している[Piggydb](http://piggydb.net/) から色々アイデアを頂きました．

### :copyright: 著作権/ライセンス/ディスクレーマー

    Copyright (c) 2014-2017 Suewon Bahng, suewonjp@gmail.com
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

* * *
更新者：Suewon Bahng   ( 2017 5月に更新 )
