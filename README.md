# 九五云客服三方取号接口规范及开发说明
三方取号是一种获取远端外呼号码源的外呼取号方式，支持所有自动外呼，是在原来的自动外呼基础上对数据源进行的扩展。使用企业可以不将数据导入云客服系统，只需提供取号接口来完成数据的读取。<br/>
[PDF文档](https://github.com/95ykf/remote_number_pull/blob/master/%E4%B9%9D%E4%BA%94%E4%BA%91%E5%AE%A2%E6%9C%8D%E4%B8%89%E6%96%B9%E5%8F%96%E5%8F%B7%E6%8E%A5%E5%8F%A3%E8%A7%84%E8%8C%83%E5%8F%8A%E5%BC%80%E5%8F%91%E8%AF%B4%E6%98%8E.pdf)
# 适用范围
本文档主要说明三方取消接口的规范及对接流程，用于开发人员对接外呼系统三方取号服务。
# 接入流程
1. 企业开发人员开发取号接口，提供取号地址
2. 通过云客服系统或API接口服务创建外呼任务，设置取号方式为三方取号并配置取号地址
3. 启动外呼任务，开始按配置取号量取号发起外呼


