# 本地项目初始化到远程（以 GitHub 为例）

- 配置 ssh key
- git init //把这个目录初始化成Git可以管理的仓库
- git add README.md //文件添加到仓库
- git add . //所有未追踪的文件全部 add 到仓库
- git commit -m "first commit" //把文件提交到仓库
- 远程创建一个空项目，并复制项目地址
- git remote add origin git@github.com:username/repo.git //关联远程仓库    
- git push -u origin main //把本地库的内容推送到远程库上