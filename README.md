# chatbox2020

## tailwindcssコーディング方法共通化 

基本的にはTailwindのクラスのみを使用する。    
position指定など、tailwindで実現しづらい場合のみコンポーネント内にcssを記述しても良い。

各セクションで使用されるボタンのような要素はコンポーネント化する。  
コンポーネントには役割に応じて先頭にprefixをつける。
UI系 UiButton.vue, UiTitle.vue  
Layout系 LHeader.vue, LFooter.vue

/components配下にあるコンポーネントはimport文を使用せずに読み込む事が出来ます。  
https://github.com/chatbox-inc/chatbox2020/issues/38

## masterNetlify
https://chatbox2020.netlify.app/

## firebase hosting
https://chatbox2020-26423.web.app/

## 各種資料

画面一覧表

コーディング規約
https://github.com/chatbox-inc/cobako_chatbox/blob/master/documents/%E3%82%B3%E3%83%BC%E3%83%87%E3%82%A3%E3%83%B3%E3%82%B0%E8%A6%8F%E7%B4%84.md

ページ一覧

## Build Setup

``` bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

## エラーが起きた時

eslint errorが起きた場合、以下のコマンドを実行する事で修正できます。  
(赤文字の黒画面）
```bash
$npm run lintfix:js
```
                                                                                                               

