git init
git clone
git checkout {branchName}  # 检出branchName分支  
git pull #拉取代码  
git pull --allow-unrelated-histories  # 拉代码时, 允许两段不相干的分支强行合并
git add #文件夹或文件名 #将文件加入到git 版本控制  
git commit 'commit message' #提交代码  
git push # 将代码push到远程指定分支，不指定分支时，push的是当前分支对应的远程分支  
git push origin {branchName} 将本地代码push到远程的branchName分支``