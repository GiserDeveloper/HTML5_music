### Html5可视化音乐播放器
----------
#### 项目技术栈总结
1、服务端：`Node + Express + ejs`
2、前端界面：`HTML + CSS(CSS3) + JS`
3、音频操作：`webAudio`
4、音频数据可视化：`Canvas`
####应用核心结构介绍
![Alt text](./1515847205333.png)
####项目搭建流程总结
<p style="color:blue"><strong>1、全局安装express</p>
`$ npm install -g express-generator`
<p><strong>2、选择ejs模板引擎，搭建项目music文件夹</p>
`$ express -e music`
<p><strong>3、进入music项目搭建项目UI</p>
`$ npm install`
<p><strong>4、全局安装supervisor</p>
`$ npm install -g supervisor` 
<p><strong>5、实现监测项目，有变化则重启服务</p>
`$ supervisor bin/www`
<p><strong>6、访问127.0.0.1:3000，后台搭建完成，整个项目结构如下</p>
![Alt text](./1515849889143.png)
