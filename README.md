# Docker Practice Repository 🐳

這個 repository 用來練習 **Docker 與容器化技術**。  
內容包含 `Dockerfile`、`docker-compose.yml`、練習範例與筆記。

---

## 📦 專案結構

- `Dockerfile` → 映像檔建置練習
- `docker-compose.yml` → 多容器服務練習
- `.gitignore` → 忽略環境檔與暫存檔
- `.env.example` → 環境變數範例
- `notes/` → 學習紀錄 & 小範例

---

## 🚀 使用方式

### 1. 建立映像檔

```bash
docker build -t my-app .
```

### 2. 啟動容器

```bash
docker run -d -p 3000:3000 my-app
```

### 3.使用 docker-compose

```bash
docker-compose up -d
```

### 4. 停止服務

```bash
docker-compose down
```
