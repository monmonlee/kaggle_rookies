# kaggle_rookies
The very first try at a Kaggle competition
哈囉大家好，我同步將github的一些指令更新到這裡👌
'''
指令	用途
git status\n	查看當前 Git 狀態（變更的檔案）
git add <檔案>	添加單個檔案到 Git 暫存區
git add .	添加所有變更的檔案
git commit -m "提交訊息"	提交變更
git push origin main	推送變更到 GitHub
git pull origin main	拉取最新的遠端版本
git log --oneline	查看提交歷史（簡要版）
git branch	查看當前分支
git checkout -b <新分支>	建立並切換到新分支
'''
## 執行步驟	
#### 第一步驟：同步資料夾	
先在你的本機建立一個放這個檔案的空資料夾	
	
1.打開 VS Code，開啟「終端機 (Terminal)」	
2.進入目前存放 Python 檔案的資料夾	
輸入"cd /path/to/your/python/files"	
4. 初始化 Git 倉庫（讓 Git 知道這是一個 Git 專案）	
輸入 "git init"	
這樣該資料夾就變成了一個 Git 倉庫。	
5.將 GitHub 倉庫設為遠端來源 (remote)	
git remote add origin https://github.com/你的GitHub帳號/你的專案名稱.git	
這樣你建的資料夾就已經和GITHUB上面連結了	
	
#### 第二步驟：將你目前的檔案上傳到GITHUB	
1. 檢查目前的 Git 狀態(應該會顯示「Untracked files」= 沒有 Git 追蹤的 Python 檔案)	
git status	
	
2.將所有檔案加入 Git 追蹤	
	
git add .	
	
3. 提交變更 (commit)	
	
git commit -m "初始化專案，新增 Python 程式碼"	
	
	
4. 推送 (push) 到 GitHub	
	
git push -u origin main	
	
#### 第三步驟 修改已追蹤的程式	
	
1. Pull (從 Git 到本地)：	
這步驟確保本地版本是最新的，避免與他人的更改產生衝突。	
	
```bash	
git pull origin main	
```	
2. 修改檔案 (檔案會被標記為 modified)： 這時你就做各種修改，寫程式、改文件等等，Git 會自動標記哪些檔案被改動了。	
3. Add (準備提交)：這步驟告訴 Git 哪些修改要被納入下一次的提交。	
```bash	
git add .  # 或指定檔案 git add specific_file.py	
```	
4. Commit (提交更改)：這步驟在本地儲存你的更改，並附上說明訊息。	
```bash	
git commit -m "你的提交訊息：描述你做了什麼修改"	
```	
5. Push (從本地到 Git)：這步驟將你的本地更改上傳到遠端儲存庫。	
```bash	
git push origin main	
```	
	
這個流程就像在寫論文一樣：先看看別人寫了什麼（pull），再寫自己的部分（修改），然後存檔（add & commit），最後交給教授（push）。	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
