# git
## master (創建新分支)
1. 將遠端拉至本地端：git clone 網址
2. 創建並切換至新分支：git checkout -b 分支名稱

## branch (在本地端的分支建檔並推至遠端)
3. 新增檔案：touch 檔名
4. 編輯完成後，推至暫存區：git add 檔名
5. 提交推送結果：git commit -m "描述內容"
6. 推至遠端：git push origin分支名稱

## master (拉取遠端 master，在本地端將 branch merge 至 master，並解決 conflict，推至遠端)
7. 切換至 master：git checkout master
8. 拉取最新遠端 master 至本地端：git pull origin master
9. 在本地端將 branch 合併至 master：git merge 分支名稱
10. 在本地端手動解決 conflict
11. 若有解決 conflict，檔案內容會更新，需再次將該檔案推至暫存區：git add 檔名
12. 提交合併結果：git commit -m "描述內容"
13. 將合併後的 master 推至遠端：git push origin master
14. 刪除本地分支 (可選)：git branch -d 分支名稱
15. 刪除遠端分支 (可選)：git push origin --delete 分支名稱

## key
- 查看 git 狀態：git status
- 查看提交記錄：git log
- 查看遠端分支：git branch -r
- 查看本地分支：git branch
- 刪除檔案：git rm 檔名
