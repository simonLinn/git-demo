# git-demo

<ul>
<h3>連接repository</h3>
  <li>添加一個repository</br>
$ git remote add < local name > < repository url >
</ul>


<ul>
<h3> 確認檔案都加入索引和git log，如果沒有就不能上傳到Github</h3>
<li>確認狀態</br>
$ git status
<li>加入索引</br>
$ git add.
<li>加入commit紀錄</br>
$ git commit -m 'Update Message'
<li>顯示歷史紀錄</br>
$ git log
</ul>

<ul>
<h3>上傳</h3>
 <li>將loacl推上master</br>
 $ git push -u < local name > master
  <li>將loacl推上dev</br>
 $ git push -u < local name > dev
</ul>
