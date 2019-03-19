### 项目介绍
   springcloud项目是在开源中国下载的，是青岛-李春光的项目clouddo。十分感谢作者将项目开源。也感谢开源中国这个平台提供的开源项目。
   clouddo是基于springcloud和vue微服务，前后端分离的后台管理框架，可以作为springcloud和vue的入门学习框架，亦可以作为一个基础脚手架进行二次开发

### 使用说明


1.新建数据库，导数数据库脚本（clouddo-admin的根目录下）,修改clouddo-admin的数据库用户密码

2.启动clouddo-server 注册中心

3.启动clouddo-zuul 网关

4.启动clouddo-base 基础微服务

5.启动clouddo-admin 权限微服务

6.启动clouddo-cms 内容管理微服务

7.启动前端项目 https://github.com/1808577500/springcloud-view.git

启动前端
4.1新开一个命令行窗口
4.2定位到项目目录并安装依赖
  > cd 你自己的位置/clouddo-view
  > npm install
4.3依赖安装成功后执行启动命令
  > npm run dev
  # 显示如下内容说明本地启动成功
  # DONE Compiled successfully in 7515ms
  # Listening at http://localhost:8081

如果启动前段报错可能是对应的依赖没有下载成功请将4.2的下载依赖命令换成

npm install -g cnpm --registry=https://registry.npm.taobao.org


### 系统截图
![输入图片说明](https://gitee.com/uploads/images/2018/0525/154945_23b93b75_1204498.png "屏幕截图.png")
