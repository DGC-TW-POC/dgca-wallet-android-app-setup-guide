# dgca-wallet-android-app-setup-guide
儲存dgca-issuance-web產生的qrcode到手機的app裡
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
### 更改 wallet-context.jsonc
- 路徑: `app/src/${tst || acc}/assets/wallet-context.jsonc`
> Android project 會在 assests 直接看到.
- versions.context.url 改成自己issuance的url
- versions.endpoints.claim.url 前面改成自己issuance的url
- 更改pubkeys

## 開始使用
- 開始畫面依據手機的螢幕鎖定設定請使用者再次驗證
![](https://i.imgur.com/gleJcrC.jpg)
- 掃qrcode
- 確認資料 (畫面是舊圖，現在step2是qrcode資料)
![](https://i.imgur.com/Bnjpvzi.jpg)
- 輸入TAN碼 (畫面是舊圖，現在step3是TAN)
![](https://i.imgur.com/LVNb4c0.jpg)
- 儲存成功
![](https://i.imgur.com/jPBUraW.jpg)
- 點開後的內容
![](https://i.imgur.com/uy4IlEO.jpg)
![](https://i.imgur.com/dVaiXuS.jpg)
