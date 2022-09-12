# ログインフォームのテンプレート

[テンプレートサイトはこちら](https://taku-web3.com/project/login-form/index.html)

## ■改めて学んだ内容

- inputタグの書き方
```html
<input type="text" name="username" placeholder="ユーザー名">
<input type="email" name="email" placeholder="メールアドレス">
<input type="password" name="password" placeholder="パスワード">
<input type="password" name="cofirmedPassword" placeholder="確認用パスワード">
<input type="submit" name="login-button" value="ログイン">
```


- inputタグのCSSでの指定方法
```css
input[type="text"],
input[type="email"],
input[type="password"] {
}
```

- ホバーしたときに色を変える
```css
input[type="submit"] {
  background-color: rgb(15, 175, 121);
}

input[type="submit"]:hover {
  background-color: rgb(15, 118, 83);
}
```

- 画像をCSSで設定して中央寄せにする。
```css
.right-box {
  background-image: url(./bg.jpeg);
  background-size: cover;
  background-position: center;
}
```