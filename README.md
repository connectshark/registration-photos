# 婚禮登記照片

這個儲存庫包含了我們婚禮登記網站所使用的照片。所有圖片都透過 jsDelivr CDN 提供，以確保快速載入。

## 使用說明

### 照片清單

所有可用的照片檔案名稱都記錄在 `photos.json` 檔案中。您可以透過以下連結取得此清單：

```
https://cdn.jsdelivr.net/gh/connectshark/registration-photos@main/photos.json
```

### 圖片連結

若要存取特定圖片，請使用以下格式的網址。圖片提供多種解析度。

```
https://cdn.jsdelivr.net/gh/connectshark/registration-photos@main/{解析度}/{檔案名稱}
```

-   `{解析度}`: 您需要的圖片解析度，可選 `1x`、`2x` 或 `4x`。
-   `{檔案名稱}`: 照片的檔案名稱 (例如：`wedding-1.webp`)。

#### 範例

-   **1x 解析度:** `https://cdn.jsdelivr.net/gh/connectshark/registration-photos@main/1x/wedding-1.webp`
-   **2x 解析度:** `https://cdn.jsdelivr.net/gh/connectshark/registration-photos@main/2x/wedding-1.webp`
-   **4x 解析度:** `https://cdn.jsdelivr.net/gh/connectshark/registration-photos@main/4x/wedding-1.webp`

## 版權

本儲存庫中的圖片採用 [CC BY-SA 4.0](LICENSE) 授權。
