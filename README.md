# express-todolist
### 安装应用生成器
```
npm install express-generator -g
```
#### 创建应用
```
express myapp //在当前目录下创建一个名为myapp的工程文件
cd myapp  //进入文件夹
npm install  //安装所有依赖包
npm start   //下载文件夹

```
#### 模板引擎
默认是jade 需要改成ejs步骤
- npm install --save ejs //安装模板引擎包
app.set('view engine', 'ejs'); //在app.js更改如下设置


### 启动
```
node app
网址打开 http://127.0.0.1:3000/todo
```

> 本项目主要练习express一些基本功能思路与实现，便于加深理解。
