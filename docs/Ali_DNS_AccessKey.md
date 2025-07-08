## 1 创建用户
打开 [**RAM 访问控制**](https://ram.console.aliyun.com/users) ，登录成功后点击“**创建用户**”，**自定义用户名称**，并勾选“**使用永久 AccessKey 访问**”，**确定**。

![](https://cdn.nlark.com/yuque/0/2025/png/764468/1751986676170-0756acaf-f67e-489f-89ec-61b6b02fe4c0.png)

创建后，复制并保存好 Access 信息

![](https://cdn.nlark.com/yuque/0/2025/png/764468/1751987018274-88466fd1-7b0f-4830-a721-903e90bc130c.png)

## 2 创建权限策略
若您需要自定全策略参考下面步骤，示例创建所有，请根据您的需求自行更改。

自定义权限策略，点击“**权限策略**” -> “**创建权限策略**” -> 搜索“**云解析dns**”并勾选。

![](https://cdn.nlark.com/yuque/0/2025/png/764468/1751987577489-94beaf61-cf7b-4167-b678-d916a1bc55ee.png)

![](https://cdn.nlark.com/yuque/0/2025/png/764468/1751987740116-a146d61d-592e-4c86-96c4-9e29e9afadb9.png)



保存的策略名称、备注自定义即可（**AlidnsFullAccess**，**公共 DNS 所有权限**）

![](https://cdn.nlark.com/yuque/0/2025/png/764468/1751987932810-61e504e4-0501-4d78-a0ef-c81f88ea3942.png)



## 3 创建授权
若您无需自定义权限，可直接使用官方默认所有权限策略，搜索“**AliyunDNSFullAccess**”。



自定义权限授权，点击“**用户**” -> “**添加权限**” ->搜索刚创建的权限名称“**AlidnsFullAccess**”并勾选，“**确认新增授权**”，至此结束。

![](https://cdn.nlark.com/yuque/0/2025/png/764468/1751988290531-8ca6c901-197a-4869-9515-7f86d3d567e6.png)

