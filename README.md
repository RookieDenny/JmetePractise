# JMeter Login API 測試練習

### 使用JMeter製作自動化 API 測試作品，針對https://reqres.in/api/login提供的API<br>
### 進行多筆帳密測試，並驗證回應是否符合預期<br>

#### 測試說明<br>
使用 CSV Data Set Config 載入多組帳密<br>
發送 POST 請求測試登入 API<br>
驗證 Response Code 是否為 200、400、401<br>
驗證回應是否包含 token 或錯誤訊息<br>