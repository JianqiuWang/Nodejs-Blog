# 使用Nodejs + Mongodb 构建多人博客系统

使用`Ejs`作为模板引擎，`nodejs`后端逻辑操作，`mongodb`进行数据存储

## 已实现功能

1. 用户登录及注册功能,使用cookie进行数据持久化
2. 实现了发表，编辑及删除博文功能
3. 实现了文章评论功能
4. 增加pv统计和留言统计
5. 增加了标签功能
6. 采用Kindeditor富文本编辑器
7. 实现了文章分页功能
8. 增加访问日志及错误日志功能
9. 实现了图片上传功能

----------
##  使用

clone源码
```
git clone https://github.com/TenderQ/node-Blog.git
```
下载依赖
```
npm install
```
打开数据库
```
mongod
```
启动应用
```
node app
```
