读书实践周作业 - Git

用户：jellyfish-0


参考：
1. Git 官方文档：https://git-scm.com/doc

2. Git 菜鸟教程：https://www.runoob.com/git/git-tutorial.html

3. GitHub 官方指南：https://docs.github.com/zh/get-started

流程：
1. 安装 Git
2. 配置 Git
3. 创建本地仓库
4. 提交代码到本地仓库
5. 推送代码到远程仓库
6. 克隆远程仓库

相关指令
 git config --global user.name "jellyfish-0"
 git config --global user.email "jellyfish-0@example.com"
 touch README.md
 git add README.md
 git commit -m "Initial commit"
 git push
在push之前，需要先创建一个远程仓库，然后将本地仓库关联到远程仓库。同时需要生成一个对应ssh连接github个人账户。