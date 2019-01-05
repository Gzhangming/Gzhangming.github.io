---
title: 
date: 2018-12-31 15:01:28
tags:
---

1 . 安装node.js

- 也可以官网下载

- 下载地址 链接：https://pan.baidu.com/s/1B3BDbJCcpVzEI6lmD0OEaQ 
     提取码：dgpq 

- 一直next下去

- 查看是否安装成功  打开命令行  输入 node -v  显示版本号说明成功

2 . 注册gitHub

- 打开官网 https://github.com/

- 不会注册的可以自行百度

- 创建项目 new repository 

- 输入项目名 必须是你的 用户名.github.io

- 勾选public 
- 勾选initializ .................

- 然后Create repositorty

- 创建成功  

3 . Git 安装

也可以官网下载（我的是w8）

-链接：https://pan.baidu.com/s/1_odiVJQ7WWfWmRC33YmjLQ 
 提取码：td45 

- 也是一直next下去

-测试是否成功  打开cmd  输入 git  有显示成功！

4 . githubSSH配置（看不懂了可以转达到git教程上进行学习）

- 打开git 命令行
- 输入 ssh-keygen -t rsa -C "自己的邮箱"
- 然后回车 

- 找到下载好的文件 （.git）
- 复制到gitHub上进行设置

5 . 使用hexo

- 打看 https://hexo.io/zh-cn/docs/ 官网

- 你想安装到哪里就在哪里创建文件夹 
- 然后右键打看git B...
- 输入  npm install hexo-cli -g 

- 等待安装 

- 初始化 hexo init 名字 （工程名字 随便）

- cd 你起得名字 

- npm install

- hexo s -p8080 (本地运行)

- 成功测试  在浏览器上输入localhost:8080  就会出现画面



6 . 部署到GitHub 上

在开始之前，您必须先在 _config.yml 中修改参数（在项目下找到）

修改最下面  

      deploy:
       type: git
       repo:
     type: heroku（git上考的地址）
     repo:

下载插件 
   执行   npm install hexo-deployer-git --save


    deploy:
     type: git
     repo: <repository url> #https://bitbucket.org/JohnSmith/johnsmith.bitbucket.io
     branch: [branch] #published
     message: [message]
     
- 执行 

      hexo -g 
      hexo -d
      
      
 如果你是第一次使用git 会报错  
 
 输入 
      
      git config --global user.name "名字"
      git config --global user.email 邮箱
      
再次执行 hexo d

访问项目名就可以看见博客了


 

 




