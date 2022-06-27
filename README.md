# login-test2

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

## パスの設定
アカウント作成
　メールアドレス入力　　　　　　/register/mailaddress-form
　メールアドレス送信完了表示   /register/mailaddress-form/complete
　登録情報入力フォーム         /register
　アカウント作成登録確認       /register/confirmation
ログイン
　認証情報入力フォーム         /login
パスワード再設定（ログイン）
　メールアドレス入力           /login/mailaddress-form
　メールアドレス送信完了表示   /login/mailaddress-form/complete
　パスワード入力フォーム       /login/resetting-password
記録画面　                    /record/:id
入力一覧画面                  /input-list/:id
分析画面                      /analysis/:id
マイページ                    
　マイページ表示              /mypage/:id
　マイページ編集              /mypage/:id/edit
　マイページ編集内容確認      /mypage/:id/edit/confirmation
パスワード再設定（マイページ） 
　メールアドレス入力          /mypage/mailaddress-form
　メアド送信済み表示画面      /mypage/mailaddress-form/complete
　パスワード入力画面          /mypage/:id/resetting-password


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
