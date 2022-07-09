## 物流授权

### 授权物流商

目前，系统打通了 云途物流、前海三态、CNE、递四方、杰航、一起飞、义达、燕文等物流，您需要先注册需要的物流商的对接账号，然后将自己的这些物流账号授权到系统，以便快速打单发货。您可以在"仓库-物流授权"菜单下添加您的物流账号。

### CNE授权

以CNE为例，注册CNE物流账号，使用您的CNE账号登录[CNE后台](https://www.cne.com/)，找到API秘钥：

![CNE授权.png](https://oss.yboom.cn/resource/guide-doc/8a0d499f10793b25b89a7bc49a942c25.png)

在系统的物流授权处新建物流，并选择“CNE”，ID和秘钥填入并提交：

![物流授权.png](https://oss.yboom.cn/resource/guide-doc/76ed5c7ed66b4bf6e3e45ea032fa0809.png)

至此您已经完成了CNE物流的授权。

很可能您开设了地址不同的多加转运中心，所以在授权完成后，您需要为刚授权的物流商指定转运中心：

![物流商设置转运中心.png](https://oss.yboom.cn/resource/guide-doc/be9c5243719d60380fb0ee22ab05c564.png)

每家物流商都提供了种类繁多的物流渠道，这回给仓库制单人员带来困扰，所以，当您完成物流授权后，需要选取哪些物流渠道是您所需要的：

![选中的渠道.png](https://oss.yboom.cn/resource/guide-doc/2dfb18d9cbdfc3fd714ec76de1dfaea1.png)

下面是除CNE意外的其他所有物流商的授权方式。

### 递四方授权

注册[递四方](https://order.4px.com/)账号，使用账号登录[递四方开放后台](https://open.4px.com/login?userType=customer)，找到APP对接，并新建申请：

![递四方注册1.png](https://oss.yboom.cn/resource/guide-doc/ad00c4f18dd7515e85fc769360eb9da5.png)

等待递四方通过审核后，在已通过一栏查看key和secret：

![递四方注册2.png](https://oss.yboom.cn/resource/guide-doc/e5937a2189b6342919ddb859464e0317.png)

获取到AppKey和AppSecret后，在系统授权递四方物流：

![递四方注册3.png](https://oss.yboom.cn/resource/guide-doc/84689af9c7c69f293039d1e80b3fe7d7.png)

**<u>注意：在物流授权时，您会发现，有的物流在系统授权时需要填写地址，有的不需要，那是因为有的物流商在官网注册账号时已经要求您填写了物流揽收地址，例如CNE，不需要再授权时再输入一次地址。而有的则需要在每次发起揽收请求时自带地址，例如递四方，需要在授权时写明揽收地址。</u>**

### 义达授权

在[义达物流官网](https://www.ydhex.com/)注册账号，并登录，然后找到API设置，新增API，选中您的用户，成功后会在表格内看到一条数据：

![义达授权.png](https://oss.yboom.cn/resource/guide-doc/e1f4cb77e572685a0f52fcf576495a60.png)

在系统中授权义达物流：

![义达授权2.png](https://oss.yboom.cn/resource/guide-doc/83435baa0d6f6185cdce2436671970db.png)

### 前海三态授权

访问[前海三态官网](https://www.sfcservice.com/)，注册物流账号并登录，找到 "个人中心"->"信息管理"->"API访问配置"，点击查看证书：

![三态授权1.png](https://oss.yboom.cn/resource/guide-doc/e1397d1ef2191bed943166073716e072.png)

到系统授权三态物流：

![三态授权2.png](https://oss.yboom.cn/resource/guide-doc/3435afdde3ac80a8fb42113e7fb4a404.png)

### 燕文物流授权

访问[燕文物流官网](https://www.yw56.com.cn/)，注册账号并登录，找到"我的信息"->"发货账号信息"

![燕文授权1.png](https://oss.yboom.cn/resource/guide-doc/94d1265081e4feee70fac68d8879f06d.png)

找到ID和秘钥后，到系统授权燕文物流：

![燕文授权2.png](https://oss.yboom.cn/resource/guide-doc/45c171672b55ead91334d53148e7875f.png)

<br/>

### 一起飞啊授权

访问[一起飞啊官网](https://www.17feia.com/)，注册物流账号并登录，找到"账户管理"->"API信息"：

![一起飞授权1.png](https://oss.yboom.cn/resource/guide-doc/9f410e8b0cffd600129d705da06e8451.png)

到系统授权一起飞物流，填写自定义的物流名称，一起飞的API Name、API Token，以及您的仓库揽收地址：

![一起飞授权2.png](https://oss.yboom.cn/resource/guide-doc/ce6838bb1ffc1446162b3fda42984a2f.png)

### 云途物流授权

访问[云途物流官网](https://www.yunexpress.cn/)，注册物流账号并登录，进入用户中心，找到API设置：

![云途授权1.png](https://oss.yboom.cn/resource/guide-doc/5d3aecdac460954939ae0bc0d2c14e1f.png)

到系统授权云途物流，这里不在赘述，参考其他物流商。

### 杰航授权

访问[杰航官网](http://xt.jiehang.net/new_index.jsp?retry_reason=PASSWORD)，注册账号并登录，找到 "管理中心"->"API申请"：

![杰航授权1.png](https://oss.yboom.cn/resource/guide-doc/8a3c1758f0ae3a694a776059da9a79c9.png)

到系统授权杰航物流：

![杰航2.png](https://oss.yboom.cn/resource/guide-doc/c73f5e9b92b83971976b2387f47f7477.png)

### 万邦授权

访问[万邦物流官网](http://www.wanbexpress.com/)，注册账号并登录，找到客户代码和秘钥，到系统授权即可。