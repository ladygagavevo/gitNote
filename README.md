# gitNote
https://git-scm.com/book/zh-tw/v2/%E9%96%8B%E5%A7%8B-%E5%88%9D%E6%AC%A1%E8%A8%AD%E5%AE%9A-Git 初次使用(剛灌git 需要設定username 與useremail)
可以用git config --list 是否設定完成

上傳至github的步驟:
1.下載git
2.對目標資料夾案右鍵並選git bash
3.登入github
4.指示碼步驟
    git init
    git add .
    git commit -m ‘first commit’
    git remote add origin 網址
    git push -u origin master

init 為創造該檔案本地資料庫，使之後變更的紀錄都可以被儲存在裡面，會創造出一個隱藏的.git資料夾 add . 將所有的檔案由工作目錄儲存到索引 commit 將修改紀錄儲存到本地數據庫 push 將本地數據庫的東西推送到遠端數據庫進行更新

為什麼要有索引的存在 https://hackernoon.com/understanding-git-index-4821a0765cf

未完
