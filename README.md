# steps
上传到GitHub步骤

### 将本地项目上传到GitHub中
cd XXX/XXX   （打开终端 进入项目的根目录 ）
git init  // 初始化git
git add . // add所有文件
git commit -m "first commit" // 提交到本地仓库
git remote add origin https://github.com/huangxin170/Test.git // 项目地址
git push -u origin master // 提交到远程库

### 拉取GitHub端代码
如果在本地中有关联的目录
直接git pull 
或者git pull origin xxx (分支名)

如果在本地中没有关联的目录 （拉取别人的代码）

cd xxx (需要保存的文件目录)
git clone  https://github.com/huangxin170/Test.git  //项目地址


