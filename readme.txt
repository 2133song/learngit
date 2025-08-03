Git is a distributed version control system.
Git is free software.

git status
git diff readme.txt
git add readme.txt

# 添加自己创建的文件夹
git add subfolder/
git commit -m "add folder subfolder"
git remote add origin git@github.com:2133song/learngit
git push -u origin master

# 添加clone的文件夹
git rm -rf cached gitskills/ # 从缓存区删除gitskills文件夹，取消Git跟踪，保留实际文件
git add gitskills/
git commit -m "add folder gitskills"
git remote add origin git@github.com:2133song/learngit
git push -u origin master