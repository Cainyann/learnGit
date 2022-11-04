//新建目录文件夹
zhiyanliu@zhishideMacBook-Pro ~ % mkdir learnGit
//cd 进入文件夹
zhiyanliu@zhishideMacBook-Pro ~ % cd learnGit
//pwd 显示目录
zhiyanliu@zhishideMacBook-Pro learnGit % pwd
/Users/zhiyanliu/learnGit
//git init初始化
zhiyanliu@zhishideMacBook-Pro learnGit % git init

//touch 新建文件
zhiyanliu@zhishideMacBook-Pro learnGit % touch readme.md

//git add
git add readme.md
//提交
git commit -m "message"

//看工作区有哪些文件被修改过
git status
//查看具体修改内容
git diff

//查看最近到最远的提交日志
git log

