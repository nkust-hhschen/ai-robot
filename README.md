# AI 機器人｜課堂互動示範

國立高雄科技大學　不分系　115 學年度第 1 學期　｜　陳泓勳

這個 repo 只放**可以直接在瀏覽器打開的互動示範頁**，給修課同學在課堂上與課後自己操作。
筆記本、投影片、作業不在這裡。

## 線上開啟

> https://＜你的GitHub帳號＞.github.io/＜repo名稱＞/

| 週次 | 示範 | 檔案 |
|---|---|---|
| 7 | 卷積濾波器互動實驗室 | `conv-filter.html` |

## 更新方式

`conv-filter.html` 是從課程資料夾複製過來的，原始檔在 `教材/demo_filter.html`。
改完原始檔後：

```bash
cp 教材/demo_filter.html 公開網頁/conv-filter.html
cd 公開網頁 && git add -A && git commit -m "更新卷積示範" && git push
```

推上去之後 GitHub Pages 約 1 分鐘內會自動更新。

## 新增一個示範

1. 把新的 `.html` 放進這個資料夾
2. 在 `index.html` 複製一個 `<a class="card">` 區塊、改掉文字與連結
3. commit、push
