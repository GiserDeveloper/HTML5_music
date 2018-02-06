### Html5可视化音乐播放器
----------
#### 项目技术栈总结
1、服务端：`Node + Express + ejs` <br>
2、前端界面：`HTML + CSS(CSS3) + JS`  <br>
3、音频操作：`webAudio` <br>
4、音频数据可视化：`Canvas`<br>
#### 应用核心结构介绍<br>
![](https://github.com/GiserDeveloper/HTML5_music/raw/master/public/media/680d34b3-f14f-4ad5-b526-43718111b979.png) <br>
#### 项目搭建流程总结<br>
1、全局安装express  <br>
`$ npm install -g express-generator`  <br>
2、选择ejs模板引擎，搭建项目music文件夹  <br>
`$ express -e music`  <br>
3、进入music项目搭建项目UI<br>
`$ npm install`<br>
4、全局安装supervisor<br>
`$ npm install -g supervisor` <br>
5、实现监测项目，有变化则重启服务<br>
`$ supervisor bin/www`<br>
6、访问127.0.0.1:3000，后台搭建完成，整个项目结构如下<br>
![Alt text](https://github.com/GiserDeveloper/HTML5_music/raw/master/public/media/fb8d0d7a-e6d0-4f8b-a9ab-f7e09877017e222.png)
