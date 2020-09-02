## 楼层列表查询


**接口地址**:`/datastoreServer/roomManage/floor/findList`


**请求方式**:`GET`


**请求数据类型**:`*`


**响应数据类型**:`*/*`


**接口描述**:


**请求参数**:


| 参数名称 | 参数说明 | in    | 是否必须 | 数据类型 | schema |
| -------- | -------- | ----- | -------- | -------- | ------ |
|AccessSecret|用户身份标识码|header|false|string||
|Authorization|令牌|header|false|string||
|buildingId|buildingId|query|false|string||


**响应状态**:


| 状态码 | 说明 | schema |
| -------- | -------- | ----- |
|200|OK||
|201|操作失败||
|403|权限错误，您无权操作此功能||
|500|系统错误，请联系管理员告知该情况||
|1000|未登录||
|1001|用户名或密码错误||
|1002|参数错误,请检查是否缺少必要参数或参数值错误||


**响应参数**:


暂无


**响应示例**:
```javascript

```