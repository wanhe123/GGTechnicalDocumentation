# 基础组件



项目名 | Pod名 | subPods|依赖私有组件 | 项目描述
------------ |------------- |-------------| ------------- | -------------
MiGuKit | MGKit |Category、MGProtocol、MGNotify、MGResource |YTKNetwork、YYKit、AFNetworking、BFKitYTKKeyValueStore | [MG的基础组件，提供包括常用工具类、网络请求、数据解析、全局宏等基础功能](http://183.192.162.101:8089/ios/MiGuKit/blob/master/README.md)
MGPlayer | MGPlayer |Model、Configure、APIHandler、BasePlayer、BasePlayerView、ViewElement、EventHandler、Player|MGApi、MGTools、MGKit、MGPlayerSDK、Masonry、MGReactiveCocoa | [播放器组件，包括基础的播放功能子模块、基础UI样式子模块、EventHandler、APIHandler以及点播用的复杂播放器](http://183.192.162.101:8089/ios/MGPlayer/blob/master/README.md)
MGEncryptWrapper | MGEncryptWrapper |无 || [计算盐值和签名](http://183.192.162.101:8089/ios/MGEncryptWrapper/blob/master/README.md)
