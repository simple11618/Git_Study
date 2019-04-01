# 测试 下载远端分支内容

## 第一种方式
	
   clone时使用-b选项指定远端分支名
   -b, --branch <branch>：checkout <branch> instead of the remote's HEAD

   - 命令
     git clone -b new https://github.com/simple11618/Git_Study.git


## 第二种方式
 
	先clone默认分支，然后在手动切换分支

   - 命令
   	 git clone https://github.com/simple11618/Git_Study.git

   	 git checkout new 

   	 