# 使用 Google Maps API 搜尋附近的飲料店

## 介紹
這個程式使用 Google Maps API 搜尋指定位置附近的飲料店。您可以輸入您的位置坐標，設定搜尋半徑和關鍵詞，然後程式將返回附近的飲料店的名稱、地址和評分。

# 使用前提 需申請google maps api
### **步驟一：API 的申請、爬 Google Map 店家資料、搞懂 API 限制**

- 在這個實際案例中，我會用 Google Map API 來取得店家資料，並且存成可以分析的資料形式 (csv)
- 首先，在這之前，需要申請 Google Map API，這個過程可以讓你了解 Google 如何把 API 授權給我們
    - 步驟一：申請帳號，付款方式備妥 (不需付費，只是需要填寫付款資訊)
    - 步驟二：申請 Google Map API 金鑰  (或參考以下說明)
    - [這邊有篇文章很仔細，可以參考](https://www.weya.com.tw/design/google-map-api-key)
- API 限制：這邊可以看到 Google Map API 的限制，我們可以先用免費的方式來使用


## 安裝必要的套件
請確保您已經安裝了必要的套件，可以使用以下指令安裝：
```
pip install -U googlemapspip
pip install -U pandas 
```

## 使用說明
1. 首先，請在程式中輸入您的 Google Maps API 金鑰。
2. 設定您的位置坐標 (經度和緯度)，以及搜尋半徑和關鍵詞。
3. 執行程式後，程式將返回附近的飲料店的資訊。
4. 結果將以 CSV 檔案格式下載到您的本地計算機上。

## 程式碼
您可以在這個 GitHub Gist 鏈接中找到完整的程式碼：[程式碼鏈接](link_to_your_code_gist)

## 範例結果
以下是搜尋結果的範例：
![image](https://github.com/tn00627974/google_maps/assets/139155210/0da63b36-3d46-4c6a-b8f7-b2dbfdfa5bfc)


## 注意事項
- 請確保您的 Google Maps API 金鑰有效且有足夠的配額。
- 請注意使用 Google Maps API 時的費用和限制。

希望這能幫助到您！如果您有任何問題，請隨時提問。
