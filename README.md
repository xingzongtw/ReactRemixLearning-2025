# 歡迎使用 Remix！

- 📖 [Remix 文件](https://remix.run/docs)

## 開發

啟動開發伺服器：

```shellscript
npm run dev
```

## 部署

首先，為生產環境構建您的應用程式：

```sh
npm run build
```

然後以生產模式運行應用程式：

```sh
npm start
```

現在您需要選擇一個主機來部署應用程式。

### 自行部署

如果您熟悉部署 Node 應用程式，內建的 Remix 應用伺服器已經可以用於生產環境。

請確保部署 `npm run build` 的輸出結果：

- `build/server`
- `build/client`

## 樣式

此模板已經預先配置了 [Tailwind CSS](https://tailwindcss.com/)，提供簡單的預設樣式體驗。您可以使用任何您喜歡的 CSS 框架。更多資訊請參考 [Vite 的 CSS 文件](https://vitejs.dev/guide/features.html#css)。
