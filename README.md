## 获取项目
- git clone git@github.com:vastyang/blog.git
- cd blog

## 初始化博客项目
### 同步博客
- npm install hexo-cli -g
- npm install
- npm install hexo-deployer-git
### 提交博客
- git add .
- git commit -m "新增xxx文章"
- git push origin hexo

## 初始化主题
### 同步主题
- git submodule init
- git submodule update
### 修改主题
- cd themes/next
- git add .
- git commit -m "修改主题xxxx"
- git push origin master
