## デザインルールの公式ブログです。


### 環境構築
- git clone
- npm install



### 記事を作成する

```
npm run create "記事タイトル"
```

### サーバを起動

```
npm run start 
```


### 記事の公開
```aidl
npm run deploy
```

### npm run と　ローカルへのhexoインストールについて
- 私の環境では、本がいローカルにhexoをインストールしているため、
```aidl
./node_modules/.bin/hexo  
```
と実行する必要があるが、package.jsonでスクリプト実行できるようにしている。



## 参考
[静的ページジェネレータHexoで作成したブログをGitHub Pagesで公開する - Steel Dragon 14106](http://raimon49.github.io/2015/04/25/create-blog-with-hexo.html)

