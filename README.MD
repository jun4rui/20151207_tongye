# 华天旅游网同业系统文档

## 参考的网站
> http://www.op166.com/default.asp

## 使用到的接口说明

- 顶部分类ID是728，放在备注里面，取分类接口
    > http://www.htyou.com/common/websinfo_queryHTClass.action?datatype=json&classId=728


- 分类对应的同行用线路用：
    > http://www.htyou.com/mobile/ipad_queryTourLine.action?featured=同行&KeyWords=泰国
    
- 取某个线路的行程数据
	> http://www.htyou.com/mobile/ipad_queryTourTeam.action?lineid=

- 取线路详细信息用：
	> http://www.htyou.com/mobile/ipad_getTourTeam.action?lineid=22482
	
## 部署
目前部署在: ```/huatian/apache-tomcat-6.0.18-hebing/webapps/tongye``` 下