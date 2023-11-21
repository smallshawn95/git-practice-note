# 📖 Git Practice Note

## 關係圖
* **Working Directory 工作目錄**
* **Staging Area 暫存區**
* **Repository 儲存庫**

![](/image/relation.png)

## 檔案狀態
* **Untracked 未追蹤**
* **Staged 已暫存**
* **Committed 已提交**
* **Modified 已修改**

![](/image/status.png)

## 基本指令
* `git init` 初始化 Git 庫
* `git clone` 下載遠端 Git 庫
* `git add` 添加檔案到暫存區
    * -a 全部檔案
* `git status` 查看檔案狀態
* `git commit` 暫存區建立新版本
    * -m 一行訊息
* `git log` 查詢版本
    * --oneline 一行顯示
* `git push` 上傳新版本到儲存庫