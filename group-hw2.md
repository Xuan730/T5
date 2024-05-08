分配圖

![分配圖](分配圖.jpg)

甘特圖

```mermaid
gantt
    title 小組專案管理作業

    section 任務
    研擬計畫 :a1, 2023-10-01, 15d
    任務分配 :a2, after a1, 2d
    資料收集 :a3, after a2 , 15d
    建立開發環境 :a4, after a3, 7d
    建立資料庫 :a5, after a4, 7d
    前端開發:a6,after a5, 140d
    後端開發:a7, after a5, 140d
    程式測試 :a8, after a6、a7, 20d
    撰寫使用手冊 :a9, after a5, 10d
    使用者訓練 :a10, after a8, 10d
    使用者測試 : a11, after a10, 10d
```

PERT圖
![PERT](PERT.jpg)

關鍵路徑
1-2-3-4-5-7-8-10-11
