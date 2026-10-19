# AI 機器人｜課堂互動示範

國立高雄科技大學　不分系　115 學年度第 1 學期　｜　陳泓勳

本 repo 只放**可以直接在瀏覽器打開的互動示範頁**，給修課同學在課堂上與課後自己操作。
筆記本、投影片與作業不在這裡（在數位學習平台）。

## 線上開啟

https://nkust-hhschen.github.io/ai-robot/

| 週次 | 示範 | 路徑 |
|---|---|---|
| W7 | 卷積濾波器互動實驗室 | `w07-convolution/` |

每一頁都是單一 HTML、無外部相依，手機與電腦都能開，離線也能用。

## 目錄結構

```
.
├── index.html              課程主目錄
└── w07-convolution/
    └── index.html          卷積濾波器互動實驗室
```

## 更新現有示範

`w07-convolution/index.html` 的原始檔在課程資料夾的 `教材/demo_filter.html`：

```bash
cp 教材/demo_filter.html 公開網頁/w07-convolution/index.html
cd 公開網頁 && git add -A && git commit -m "更新卷積示範" && git push
```

推上去後 GitHub Pages 約一分鐘內自動更新。

## 新增一個示範

1. 建一個 `wNN-主題/` 資料夾，把 HTML 放進去命名為 `index.html`
2. 在 `index.html` 複製一個 `<a class="card">` 區塊，改掉週次、標題與連結
3. commit、push
