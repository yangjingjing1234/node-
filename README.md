# node-小结

<p>用node 开个简单的服务，安装步骤自行百度，装个node ,wwindow 环境安装后缀（.msi）</p>
<p>windows:NodeJs+Express构建项目</p>
<p>进入我的电脑→属性→高级→环境变量。在系统变量下新建“NODE_PATH”，输入“C:\Program Files\nodejs\node_global”。上边环境变量为%NODE_PATH%</p>
e:目录>express mytest 创建mytest项目 自动生成很多目录，里面有package.json npm需要安装的东西
e:目录>mytest>npm install  安装package.json里面的东西
e:目录>mytest>node bin/www   启动项目啦
浏览器访问   http://127.0.0.1:3000/

启动方法2
e:目录>mytest>node app.js  这个要在app.js里加一句话
浏览器访问   http://127.0.0.1:9000/
app.listen(9000); （修改监听端口）
module.exports = app;


