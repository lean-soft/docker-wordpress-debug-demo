# 使用容器桌面工具开发调试WordPress应用

## 第1步：克隆WordPress代码到客户端本地
git clone https://github.com/lean-soft/docker-wordpress-debug-demo.git

## 第2步：配置xdebug监听IP以及端口
更新项目根目录下的xdebug.ini文件，修改xdebug.remote_host对应的IP为客户端本机IP地址 </br>
例如：xdebug.remote_host=192.168.1.101

## 第3步：导入WordPress项目

![alt text](./images/readme-import-project.png)

## 第4步：运行WordPress开发调试环境

![alt text](./images/readme-run.png)

## 第5步：打开WordPress源代码

![alt text](./images/readme-dev.png)

## 第6步：设置应用程序断点，启动DEBUG

![alt text](./images/readme-breakpoint.png)

## 第7步：在浏览器中打开wordpress站点，并导航至断点对应的页面进行调试

![alt text](./images/readme-open-website.png)

![alt text](./images/readme-debugging.png)
