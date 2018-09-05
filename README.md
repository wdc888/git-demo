1.创建并提交一个本地项目到github（create a new repository on the command line）
echo "# git-demo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:wdc888/git-demo.git
git push -u origin master

2.提交一个存在的本地项目到github（push an existing repository from the command line）
git remote add origin git@github.com:wdc888/git-demo.git
git push -u origin master