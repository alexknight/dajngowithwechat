# dajngowithwechat
用django开发的图灵机器人
----------------------------------------------
微信的post请求格式是xml，所以django需要做的就是将xml请求解析出来，把content发送到图灵机器人接口，
接口返回的json数据把主要内容给解析出来，然后重新封装成xml返回给微信客户端。

----------------------------------------------
图灵机器人地址：http://www.tuling123.com/openapi/
