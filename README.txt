提交更改：
git commit -m "readme更新1203"


推送代码到远程(首次)：
git push -u origin master
推送代码到远程：
git push origin master

关联远程库：
git remote add origin git@github.com:gyuuee/soft001.git

git remote add origin git@server-name:path/repo-name.git

推送
 git push --set-upstream origin master
git push -u origin master
git remote -v
拉
git pull origin master

#git pull origin master --allow-unrelated-history
git pull origin master --allow-unrelated-histories
第二次

git@github.com:ThreeSquirrelsZGZ/LabGAMSystem.git
https://github.com/ThreeSquirrelsZGZ/LabGAMSystem.git
1.关联远程库：
git remote add origin 
2.拉取资料
git pull origin master --allow-unrelated-histories
3.解决冲突
新的分支：git checkout -b feature1
添加冲突文件：git add try.txt
提交冲突文件：git commit -m "120401"
4.提交文件
git push -u origin master

