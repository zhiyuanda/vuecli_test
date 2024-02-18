# 使用vue-cli构建一个项目并上传到GitHub，生成在线预览地址
>   参考来源：
>
> [前端小白如何快速上手Vue框架(下篇)_Logbook的博客-CSDN博客_如何快速搭建vue框架](https://blog.csdn.net/aaaaaab_/article/details/88171234?spm=1001.2014.3001.5506)
>
> [vue项目上传github--提供demo入口 - 简书](https://www.jianshu.com/p/13df61095961)

## 效果展示：

![img](https://img-blog.csdnimg.cn/09f6e4e141884c3bac4e4dc6359e28ff.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

## 主要功能：

使用vue-cli构建一个项目并上传到GitHub，生成在线预览地址


## GitHub地址如下：（若加载较慢建议刷新后耐心等待一会~）

https://github.com/jiang-lijun/vuecli_test

## 预览地址：

https://zhiyuanda.github.io/vuecli_test/dist/index.html#/

## 步骤如下：

### 一、安装

```
node -v
vue -V
```



![img](https://img-blog.csdnimg.cn/b980b7fb173f453eb8d2a7b3051cc2d0.png)

 ![img](https://img-blog.csdnimg.cn/a77f31b9abbf4bd09f1e428ce5827b81.png)
### 二、构建一个项目

语法：

```
vue init <template-name> <project-name>
```


 <template-name>：模板名称

<project-name>：项目名称

使用官方模板： 

```
vue init webpack vuecli_test
```


![img](https://img-blog.csdnimg.cn/f1a79b5ea15543d4886638f801991b2f.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

![img](https://img-blog.csdnimg.cn/4618958cce144436980220046f3ce360.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

### 三、运行项目

```
cd vuecli_test
npm run dev
```


 ![img](https://img-blog.csdnimg.cn/f3d9070e1d5e4e9c9b78d753c80bc054.png)

![img](https://img-blog.csdnimg.cn/7ca5b2e7e7ee454395841ad7039a41fb.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

###  四、在浏览器打开，输入url

![img](https://img-blog.csdnimg.cn/71964ee0d34e476083f649af74942415.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_17,color_FFFFFF,t_70,g_se,x_16)

![img](https://img-blog.csdnimg.cn/09f6e4e141884c3bac4e4dc6359e28ff.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

###  五、创建的项目目录

![img](https://img-blog.csdnimg.cn/10e57c64169c4ab2a95146b516f8d1d1.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

###  六、将本地项目部署到GitHub上

#### 6.1. GitHub上新建仓库：


![img](https://img-blog.csdnimg.cn/30f8ad227dff479e97077060085b3969.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)
#### 6.2. 进入本地项目根目录下：

![img](https://img-blog.csdnimg.cn/99c3679dcc7e404ea639c05a098e1049.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

 #### 6.3. 在空白区域右击鼠标：

![img](https://img-blog.csdnimg.cn/83c6912b7ff340999036bedf44bb0a8e.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

#### 6.4. 进入Git Bash Here并输入以下命令（记得把刚刚启动的本地服务先关闭，按CTRL+c退出）:

##### 6.4.1. 创建本地仓库

```
git init
```



![img](https://img-blog.csdnimg.cn/80f1b66627a342ac85d6c0a2721e7123.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

 6.4.2. 添加

```
git add .
```



 ![img](https://img-blog.csdnimg.cn/61db43ba9daf48caa1247b886de2679b.png)

 ##### 6.4.3. 提交到本地仓库，并添加注释

```
git commit -m "vuecli_test"
```


 ![img](https://img-blog.csdnimg.cn/2f00defa71f84ccebe0be9443916d2e4.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

##### 6.4.4. 连接远程仓库

```
git remote add origin git@github.com:xxx/vuecli_test.git
```


##### 6.4.5. 推送到远程仓库

```
git push origin main
```



![img](https://img-blog.csdnimg.cn/680418265bb842549b23e1f362cf3c53.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

##### 6.4.6. 查看GitHub，已成功上传

### ![img](https://img-blog.csdnimg.cn/dbd80f6968724d7ebd507313bf5d7f38.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

##### 6.4.7. 生成项目入口

```
npm run build
```

 报错：![img](https://img-blog.csdnimg.cn/975c1e0005954250915df755f55d7be4.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

解决方法：

 ![img](https://img-blog.csdnimg.cn/cd89b23a1af945ecac49b79105d54917.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_19,color_FFFFFF,t_70,g_se,x_16)

 ![img](https://img-blog.csdnimg.cn/8760fcc2294445819c5b60dac5afdc22.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

![img](https://img-blog.csdnimg.cn/6e9fad891a3943148c149cc03e5367a4.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)
##### 6.4.8. 生成项目入口文件

![img](https://img-blog.csdnimg.cn/50c99ed8824e4851894fe7f239a0cdca.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

![img](https://img-blog.csdnimg.cn/dd7d58340e8143d4a1d9ebd785afa5b8.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

##### 6.4.9. 重新提交到GitHub

```
git add -f "dist"
```



```
git commit -m "update"
```



![img](https://img-blog.csdnimg.cn/f7fdf45394144ce8bab0b9de4129e2f9.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

```
git push origin main
```



### ![img](https://img-blog.csdnimg.cn/6b852f98d4b24ad69eb5028d43d0d979.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

### 七、GitHub配置pages，生成在线预览地址

![img](https://img-blog.csdnimg.cn/7a09a8b8512b425dbd12c0ea5a3e53ca.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

 配置完成(在线预览的demo地址需要在生成的地址后面加上 dist/index.html)

![img](https://img-blog.csdnimg.cn/e18b1711263b483f93a08ebfcb86be0f.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

 ![img](https://img-blog.csdnimg.cn/6db7954eb6324bc3a1f25b9c3b828655.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAaGFjYWxpbGk=,size_20,color_FFFFFF,t_70,g_se,x_16)

 预览地址


https://zhiyuanda.github.io/vuecli_test/dist/index.html#/

# vuecli_test

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
