1、git init
作用：本地目录初始化为一个本地仓库

2、git remote add [key] [value]
作用：给本地仓库添加一个中央仓库的地址
[key] 表示在本地给中央仓库地址([value])起一个别名(一般来说 origin 用的很多，所以默认大家都以 origin 作为中央仓库的名称)
例如：git remote add cat https://github.com/QAQ333h/grainRain.git

3、git remote -v
作用：查看本地仓库的中央仓库列表

4、git remote rm [key]
作用：删除指定名称为 key 的中央仓库

5、git push [key] [branch] (-u 第一次添加需要加)
