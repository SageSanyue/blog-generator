#在Windows电脑中虚拟机Linux环境Deepin下安装Hexo
1.在Linux自带终端内配置git命令
  `sudo apt-get install git`
  然后设置用户名和邮箱地址，再git config --list检查配置；
  再配置ssh公钥；
2.安装node
  \```
  sudo apt-get install node.js
  sudo apt-get install npm
  \```
 3.安装Hexo;
  `sudo npm install -g hexo-cli`
 4.`cd ~/Desktop`
   `hexo init myBlog`
   `cd myBlog`
   `npm i`
   `hexo new 开博大吉`
   
