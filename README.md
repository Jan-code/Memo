# Memo
首次clone代码,或pull同步master代码,在master分支上建立自己的git分支，并切刀自己分支开发
例： git checkout -b ningjing 建立eric分支，并切到eric分支
cd oa/
git checkout -b [branchName]

开发中。。。。

开发完成先提交代码到本地，以防丢失，每日一次
git add [path]/[file]
git commit -m [message]

拉取master分支代码，合并团队他人提交到master上的代码 若出现类似reject冲突协商解决
git pull -r origin master

推送代码到自己的远端分支
git push origin [branchName]

进入gitLab客户端提交pull request
