# Tried to use Nuxt.js

---

## Nuxt.js とは

Vue.js でのSSR(サーバーサイドレンダリング)が簡単にできる Web フレームワーク

URL: https://ja.nuxtjs.org/

---

## Vue.js とは

"たまに動くテンプレートエンジン"

* [DEMO1](./tried_to_use_nuxtjs/vue-example.1.html)
* [DEMO2](./tried_to_use_nuxtjs/vue-example.2.html)

---

## Vue.js には問題がある

＿人人人人人＿  
＞　SEO　＜  
￣Y^Y^Y^Y￣  

---

### どうするか

そこで SSR ですよ

→ だから Nuxt.js

---

## 実際に使ってみよう

---

### npm をインストールする

nvm: https://github.com/creationix/nvm
```
# nvm をインストールする
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash

# インストールできる npm のバージョンを確認する
nvm ls-remote

# 指定したバージョンをインストールする
nvm use node 10.x.x

# npm がインストールされたか確認する
npm -v
```

※ Windows はインストーラー推奨

---

### Nuxt.js のプロジェクトを作る

```
npx create-nuxt-app <project-name>
```

プロジェクトのテンプレートができました

---

### プロジェクトを見てみる
