"# discuss-python" 

<a href="https://www.youtube.com/watch?v=LBtT1pxqsJc&feature=youtu.be">github新專案的建立與Anaconda3(python)的使用</a><br>
~~~
先安裝Anaconda3以及git的軟體。

在文件路徑C:\Users\iachievedream新增一個資料夾"discuss-python"(iachievedream是我的使用者名稱)

使用windows的搜尋開啟cmd(命令提示字元) 
輸入:cd C:\Users\iachievedream\discuss-python
cd的功能是切換到此資料夾中。

git初次使用需輸入基本資料的內容(請輸入自己的信箱以及使用者名稱):
git config --global user.email "iachievedream@gmail.com"
git config --global user.name "iachievedream"

上傳該資料夾的專案內容:
git add .                                                              //新增檔案
git commit -a -m "update content"                                      //輸入上傳的註解及其紀錄
git remote add origin https://github.com/iachievedream/discuss-python  //推送(上傳)github的專案(discuss-python)上面
git push -u origin master                                              //正式推送
~~~