## it-monitor是什么?
![image](http://vipkshttp1.wiz.cn/ks/share/resources/1f38ac91-4737-41fe-b5ce-d4e364a74ef7/975d2057-27dd-4cad-84c1-0a6e36012f21/index_files/65714622.png)

是一个监控平台旨在让用户导入服务器信息即可完成基础指标的信息监控。
除了监控服务器还可以进行二次开发扩展监控任意类型的组件，如（Tomcat、进程、Redis、
MySQL等）

## it-monitor有哪些模块？
* 数据收集器
    * 接收agent上发的数据并进行数据格式化处理
* 告警判定器
    * 判定收集器接收的数据是否触发告警事件
* 告警发送器
    * 发送判定器生成的告警事件给指定的项目组
* api接口
    * 提供页面操作的所有接口
 
## 开发进度
目前处于版本构思中，以后会慢慢添加功能


## 感谢
本系统参考 https://github.com/open-falcon 开发



