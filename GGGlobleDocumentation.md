### GGGloble文档介绍

GGGloble是项目的全局公用模块，它包括主要包括项目中用到的一些工具、通知以及模组的配置。  

 >GGGloble.h主要是对项目的基础宏定义和基础方法实现


##### 1、Utils工具类
Utils 里面放置一些常用的工具类
>StockToastHelper loading工具类(旋转的蓝色菊花)  
>TimeConversion 时间转换类

##### 2、MessageCenter通知类
 >GGBaseManager 代理管理类（主要是对代理的增删查操作）  
 >StockMessageCenter GGStock里的代理管理与通知回调
 >SubscriberCenterManager 登录的代理管理与通知回调


##### 3、GGMoudleConfigs配置类
>GGWebViewConfig WebView文件配置
>GGWebConfig 网页链接配置与跳转配置以及协议
>GGSubscriberConfig 订阅者配置以与协议
>GGHttpConfig 网络环境配置与协议
>GGStockConfig 股票文件配置与协议
