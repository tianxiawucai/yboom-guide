## 仓储管理

### 货架管理

您可以为您的转运中心定义多个货架区域，在签收库存时，系统将根据您的货架定义自动生成获取存放编码，并可以打印。

打开 "仓库-货架管理" ，可以查看已有货架区，也可以创建新定义：

<img src="https://oss.yboom.cn/resource/guide-doc/6a6c17a24e0ef81ae2996c72a47b733e.png" alt="截图" style="zoom:100%;" />

有了货架定义，在仓库签收入库货物时就可以直接选择对应的货架区自动生成入库编码和打印标签，下文将继续介绍。

### 库存管理

对于卖货用户

可以在“订单”模块下的“库存”菜单查看库存列表，点击详情可以看到历史采购的所有产品，以及购买时的价格、仓库签收状况等信息：

![截图](https://oss.yboom.cn/resource/guide-doc/040880246ccca8cfbbfd398aaaccfe58.png)

您可以在详情页中点击丢弃来通知仓库不再需要此商品，后续我们也会加入退货功能。

### 备货

当某商品卖的不错的时候，您可能选择提前筹备一些货物，您可以在订单详情页商品条目的asin码旁边找到备货按钮：

![截图](https://oss.yboom.cn/resource/guide-doc/cb8033927cdc8ccae5589b08c94b9fb9.png)

点击备货，将自动拉取商品listing，并在listing基础上创建对应库存，然后自动跳转到库存页面：

![截图](https://oss.yboom.cn/resource/guide-doc/0d0004f9834a92e322cda13872b6e43b.png)

### 留库

当您已经创建了采购单，而订单出现了状况，不再需要发货时。您可以一键将采购单留作库存：

![截图](https://oss.yboom.cn/resource/guide-doc/f3a2dbfb522658eee289361b7440165b.png)

### 签收入库

当有业务员操作了备货或留库，那么对应仓库的管理员就可以在 "仓库"-"入库单" 菜单下看到相应的入库单，并支持签收操作。

<img src="https://oss.yboom.cn/resource/guide-doc/bbcbb99fa22d8542150b9ede15d64178.png" alt="截图" style="zoom:100%;" />

签收完成后，您将看都签收后系统自动分配的库存编码，点击打印，可以讲标签和其相关信息打印出来：

![截图](https://oss.yboom.cn/resource/guide-doc/268dea066f272a7ce78f9100f9e8d5f8.png)

打印的标签包括了签收时生成的货架编号、货物所属公司的负责人和联系电话、相关卖货业务员的姓名和联系电话。

<br/>

### 调拨出库

在采购时，如果您知道已有某产品在库存中，处于可售状态，则可以直接通过asin搜索选取对应的库存，来建立调拨采购单：

![截图](https://oss.yboom.cn/resource/guide-doc/55a36f391790666601c49a3dbf0cfc11.png)

这样在仓库建单时，也会有扣减库存的选择，并且会默认被选中：

![截图](https://oss.yboom.cn/resource/guide-doc/4d4b02ecd4e4eae9064b6e3eed9e9c55.png)