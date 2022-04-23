# weibo-search-keyword-bot
This is a code to scrape tweets from Weibo(微博) based on keywords searched.  
I tried to scrape Weibo tweets based on the keywords I searched for, but I could not find such a code, so I decided to write this code.  
As I am a beginner in programming, I would appreciate any suggestions for improvement.

# Features
 
このコードは検索したキーワードに関するWeibo(微博)のツイートを制限なく取得することができ取得結果をCSVファイルで出力します．  

This code allows you to scrape Weibo tweets related to the searched keywords without limitation and output the scraped results in a CSV file.


# Requirement

## Programming languages 
* Python(Jupyter Notebook)

## Module
* selenium
* time
* bs4
* random
* csv
* numpy
* tkinter
* os

## App
あなたの使用しているスマートフォンにWeiboをインストールし，アカウントを作成しておいてください.  
そのアプリはログイン認証を行う際に使用します．  
Please install Weibo on your smartphone and create the account.  
The application is used for login authentication.

## Driver
chromedriverをインストールする必要があります。  
https://chromedriver.chromium.org/downloads. 

お使いのChromeのバージョンに合わせて、上記のURLからインストールして、クローンしたフォルダの中にドラッグしてください。

 You will need to install chromedriver.  
https://chromedriver.chromium.org/downloads

Depending on the version of Chrome you are using, install it from the URL above and drag it into the cloned folder.


# Installation
bs4をインストール際はpip3と入力しないとエラーが発生するため注意してください．  
Note that an error will occur if you do not type pip3 when installing bs4.

 
```bash
pip install selenium
pip install time
pip3 install bs4
pip install random
pip install csv
pip install numpy
pip install tkinter
pip install os
```
 
# Usage
まずは，githubから私のフォルダをクローンしてください．  
コードを実行したら，Weiboアイコンをクリックして，画面の指示に従ってください．  
ログイン認証の際に，あなたのスマートフォン（Weiboアプリ）を使用します．  

First, please clone my folder from github.  
Once you have executed the code, click on the Weibo icon and follow the on-screen instructions.  
Your smartphone (Weibo app) will be used to authenticate your login.  

```bash
git clone https://github.com/Kou-NGM/weibo-search-keyword-bot
```
 
# Note
くれぐれもWeibo社のサーバーに負担をかけるような変更・使用はやめてください．  
Please do not change and use anything that will overload Weibo's servers.
 
# Author
 
* Ko Nagumo航南雲
* Niigata University

 
# License
 
"weibo-search-keyword-bot" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
 

