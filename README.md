# Cloud-Genshin-Impact
云●原神 每日自动签到送15分钟脚本。

使用腾讯云函数脚本部署，定时任务触发自动签到，最高可免费获得10小时的免费时间。

## 使用说明
1，抓包获取token和device_id，填入main.py对应的位置。  
2，进入腾讯云函数页面新建云函数。  
3，运行环境选择Python3.6（3.7及之后的版本云函数不自带依赖，需另行安装，避免麻烦，直接选择3.6版本即可）。  
4，提交方法为在线编辑，将main.py代码拷贝进index.py。  
5，添加定时任务触发器，参考Corn(0 1 4 * * * *),每天4点1分触发执行。  
6，添加成功之后，进入函数管理->函数代码，往下拉，找到测试按钮，点击测试,显示测试成功即可。  

![image](https://user-images.githubusercontent.com/26202838/151330669-9afb73c7-baec-456e-b5a0-14ec36a66040.png)
![image](https://user-images.githubusercontent.com/26202838/151330610-db0d3730-6c6a-4616-ac26-0d9e82489d57.png)
![image](https://user-images.githubusercontent.com/26202838/151331275-e40922b6-fa50-42c1-b696-de14934e7c14.png)
![image](https://user-images.githubusercontent.com/26202838/151331990-ac740b9e-e381-4201-b995-a237a81f7e03.png)



### 联系方式
QQ:2218890669  
WX:同QQ
