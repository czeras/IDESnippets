# IDESnippets

#### 介绍
开发中常用的代码块

#### 软件架构
软件架构说明

## xcode 安装教程

##### 一、XCode代码块所在位置

```
~/Library/Developer/Xcode/UserData/CodeSnippets
```
##### 二、打开终端，把CodeSnippets文件夹上传到码云
```
cd ~/Library/Developer/Xcode/UserData/CodeSnippets
git init
git add .
git commit -m "Init code snippets"
git remote add https://gitee.com/czeras/CodeSnippets.git
git push -u origin master
// 加上-u参数，下次直接输入git push即可
```

##### 三、新建UpdateCodeSnippets.sh（批处理），执行后自动同步修改到码云。
```
! /bin/bash
cd ~/Library/Developer/Xcode/UserData/CodeSnippets
git pull https://gitee.com/czeras/CodeSnippets.git
git add .
git commit -m "New code snippets"
git push
echo "done"
```
##### 四、首次下载需要克隆Git，在CodeSnippets上级目录执行
```
git clone https://gitee.com/czeras/CodeSnippets.git
```





## vscode 安装教程

##### 一、vscode 代码块所在位置

```
/Users/czera/Library/Application Support/Code/User/snippets/dart.json
```








#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
