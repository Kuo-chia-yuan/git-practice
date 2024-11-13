# git
## master
1. 將遠端拉至本地端：git clone 網址
2. 創建並切換至新分支：git checkout -b feature/分支名稱

## branch
3. 新增檔案：touch 檔名
4. 推至暫存區：git add 檔名 + git commit -m "描述內容"
5. 推至遠端：git push origin feature/分支名稱

## master
6. 切換至 master：git checkout master
7. 拉取最新遠端 master：git pull origin master
8. 將 branch 合併：git merge feature/分支名稱
9. 在遠端點擊 "Compare & pull request"，手動解決 conflict
10. 將合併後的 master 推至遠端：git push origin master
11. 刪除本地分支：git branch -d feature/分支名稱
12. 刪除遠端分支：git push origin --delete feature/分支名稱

## key
- 查看 git 狀態：git status
- 查看提交記錄：git log
- 查看遠端分支：git branch -r
- 刪除檔案：git rm 檔名
