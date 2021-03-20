git使用

创建账号

```
$ git config --global user.name"lyx975"
$ git config --global user.email"1262687293@qq.com"
```

初始化（将一个目录变成git可以管理的仓库）

```
$ git init
出现了.git文件夹
```

查看当前状态

```
$ git status
```

在项目中加入文件

```
$ git add 文件名称
```

完成一个版本快照

```
$ git commit -m '版本信息备注'
```

版本更新记录

```
$ git log
```

推进进展，更新版本

```
$ git add 文件名称	这是暂存
$ git commit -m '快照名称'	做出变更
```

返回到之前的版本

```
$ git reset --hard HEAD^
```

将github上的远端仓库和本地仓库关联起来

```
$ git remote add origin 'github的仓库链接'
```

将本地仓库推送到远端的master

```
$ git push -u origin master
```

将GitHub上的东西原封不动的克隆下来

```
$ git clone 地址链接
```

每次在本地更改之后都需要同步到GitHub上面

```
$ git push -u origin master
```

