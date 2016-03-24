# Simple-Use-of-git
Simple use of git by command line
最基本的git操作：
1.在web上新建一个仓库，ps：没找到用命令行的方式新建仓库
2.在本地的某个空件夹 or 某个你想要上传的件夹下运行git init，这样该件夹变成一个仓库
3.在该件夹下，添加远程仓库(你在web创建的空仓库:git remote add origin https://github.com/这里写你的名字/你建的空仓库名字.git),
4.将远程空仓库的一个分支拉到本地，git origin pull master
5.在本地修改或添加件后，git add .    git commit -m "你的注释"
6.git push -u origin master
7.done
