# 宸定精舍官方網站

如宸法師弘法道場官方網站，使用 [Astro](https://astro.build) 建置的靜態網站。

## 網站頁面

| 頁面 | 路徑 | 說明 |
|------|------|------|
| 首頁 | `/` | 法師介紹、道場簡介 |
| 關於法師 | `/about` | 如宸法師簡介與行誼 |
| 弘法活動 | `/activities` | 共修、慈濟活動 |
| 道場介紹 | `/temple` | 宸定精舍環境與資訊 |
| 聯絡方式 | `/contact` | 地址、電話、地圖 |

## 本地開發

```bash
npm install
npm run dev
npm run build
npm run preview
```

## 部署

本網站部署於 [Cloudflare Pages](https://pages.cloudflare.com/)。

- Build command: `npm run build`
- Build output directory: `dist`
- Node.js version: `18`

## 技術規格

- **框架**: Astro 4.x
- **樣式**: 純 CSS（禪意簡約風）
- **字體**: Noto Serif TC（Google Fonts）
- **部署**: Cloudflare Pages
- **語言**: 繁體中文
