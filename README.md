# dgca-wallet-android-app-setup-guide

## 下載
```
git clone https://github.com/eu-digital-green-certificates/dgca-wallet-app-android.git
git clone https://github.com/eu-digital-green-certificates/dgca-app-core-android
git clone https://github.com/eu-digital-green-certificates/dgc-certlogic-android.git
```
> 請放在同一目錄
```
android-app
|___dgca-wallet-app-android
|___dgca-app-core-android
|___dgc-certlogic-android
```
## 設定
- Build Variant (可選擇tst or acc)
> 上方選單->Build->Select Build Variant
- 更改 `app/src/${tst || acc}/assets/wallet-context.jsonc`
> Android project 會在 assests 直接看到
