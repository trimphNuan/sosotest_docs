# DUBBO接口测试


## DUBBO接口添加
首先进入```数据服务``` ```DUBBO接口```页面 添加
![图片](/image/接口测试平台DUBBO接口添加.png)
![图片](/image/接口测试平台DUBBO接口添加case.png)
输入接口名称(必填),接口描述(必填),业务线,准备信息,执行信息(必填),断言,[保存]即可.

## DUBBO接口查询

![图片](/image/接口测试平台DUBBO接口查询.png)
可根据接口创建人、接口编号、接口名称、接口描述、系统system、服务serviceClass、接口method、业务线、模块条件匹配查询

## DUBBO接口使用

![图片](/image/接口测试平台DUBBO接口使用.png)

根据case所需测试环境,选择页面底部已配置的环境点击执行

## DUBBO接口操作

![图片](/image/接口测试平台DUBBO接口操作.png)

点击 ```查看``` 按钮查看接口详情,点击 ```复制``` 按钮可以复制接口编辑调试后[保存]成新的接口,
点击 ```删除``` 按钮删除接口,点击```编辑``` 按钮可修改接口并进行调试

## DUBBO接口导入日志

![图片](/image/接口测试平台DUBBO接口导入日志.png)

文件上传成功解析后,页面底部有[开始导入]按钮,对于平台解析出的用例，可进行导入，或是删除不需要的用例后再导入
平台有对历史的用例进行去重：去重是根据接口，方法，及请求参数的key一致性
导入后，可查看及编辑用例

