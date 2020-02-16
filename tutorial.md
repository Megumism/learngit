# gitlearn

本文件夹储存依照[廖雪峰官网 wiki](https://www.liaoxuefeng.com/wiki/896043488029600)提供的教程进行学习产生的文件。
[git 常用十类命令](https://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html)

## 笔记

### Git 多平台换行符问题(LF or CRLF)

摘要：也就是让代码仓库使用统一的换行符(LF)，如果代码中包含 CRLF 类型的文件时将无法提交

```shell
$ git config --global core.autocrlf false
0
$ git config --global core.safecrlf false
```

<http://blog.konghy.cn/2017/03/19/git-lf-or-crlf/>
