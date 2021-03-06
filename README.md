# Xmot  
This a simple Android app which helps you look up meanings of french words **offline** and **online**. You can also recite words and store them in your local **notebook**. The conncetion between server and client is based on **TCP**.

<img width="500" height="400" src="https://github.com/halflkaka/Xmot-French-WordTutor/blob/master/Images/WelcomUI.png"/>  

## Usage/使用方法
`javac androidserver.java`  
`java androidserver`  

Then your android device can connect to your server. Remember to change the IP address in MyTCPConnection.  

## Basic functions/基本功能
### Database/词库
Lingoes Dictionary：法汉词典  
You can download [here](http://www.lingoes.cn/zh/dictionary).

### Search word meanings/查单词
Search on the **local database** first. Then send request to the server, server will look up the word on [法语助手](http://www.frdic.com) and send the meaning back to the client.  

<img width="500" height="800" src="https://github.com/halflkaka/Xmot-French-WordTutor/blob/master/Images/Searchword.png"/>  

### Recite words/背单词
#### Rocket Recitation Mode/极速背词
Thanks to the [Swpieable-Cards](https://github.com/kikoso/Swipeable-Cards) provided by kikoso.  

<img width="500" height="700" src="https://github.com/halflkaka/Xmot-French-WordTutor/blob/master/Images/Rocket.png"/>  

Every time ten words randomly selected from the local database will be displayed.  
#### Normal Recitation Mode/顺序背词
For the wrong answer, a message of "Wrong Answer" will display. At the same time, it will send a message to the server and store the word in your notebook on server.  

<img width="500" height="800" src="https://github.com/halflkaka/Xmot-French-WordTutor/blob/master/Images/normal.png"/>  

## Login/用户登陆
Make sure that you have set the right IP address in class **MyTCPSocket**.  

![IP](https://github.com/halflkaka/Xmot-French-WordTutor/blob/master/Images/IP.png)  
![Wifi](https://github.com/halflkaka/Xmot-French-WordTutor/blob/master/Images/wifi.png)   

The new user should register at first and then log in. 
 
<img width="500" height="800" src="https://github.com/halflkaka/Xmot-French-WordTutor/blob/master/Images/login.png"/>  

## Contact
halflkaka https://github.com/halflkaka raphael_shi@foxmail.com  
ldihao https://github.com/ldihao ldihao@gmail.com  
Sylvain-ssy https://github.com/Sylvain-ssy 514092804@qq.com

**We are looking forward to your contribution!**


    
