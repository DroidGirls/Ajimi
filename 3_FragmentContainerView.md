## 第25回 オンライン味見会 : 
https://droidgirls.connpass.com/event/202918/

## 1.本日のお題

FragmentContainerView

https://developer.android.com/reference/androidx/fragment/app/FragmentContainerView

FragmentContainerView は、タグや FragmentManager で Fragment を追加する先のViewGroup（FrameLayout とか）  
の代わりに使うことが推奨されている View で、androidx.fragment に用意されています。

## 2. 使ってみる

①お試し導入


https://developer.android.com/reference/androidx/fragment/app/FragmentContainerView


※以下dependenciesに追加

```
implementation 'androidx.fragment:fragment-ktx:1.2.5'
```

②
コードから追加するパターンと、
xmlからandroid:nameを指定して追加するパターンを試す

https://developer.android.com/guide/fragments/create#add

https://developer.android.com/guide/fragments/transactions



## 3. 閲覧したその他資料

https://medium.com/androiddevelopers/fragments-rebuilding-the-internals-61913f8bf48e
