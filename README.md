# itfxq_erp
强烈推荐, 该项目是基于SSM的ERP进销存项目，通过该项目直接解决了日常进货也就是采购，销售，库存上的问题。直接通过该项目，可以方便的记录货品的信息，货品的销售情况，货品的库存情况等企业或者公司的经营状况。该系统 包含了进销存的方方面面，非常值得学习和使用。强烈推荐。

#### 软件技术

Springmvc

Spring

MyBatis

SpringBoot

SpringSecurity

Bootstrap

jquery

html 等....


#### 系统功能



 系统登录 -- 系统用户普通方式登录。

系统登录 --系统用户人脸识别方式登录。

系统登录 --后台权限认证，只有登录过的用户才能访问到系统后台。

系统主页—用户头像展示.

系统主页—加载用户菜单

系统主页—用户退出功能

系统管理—用户维护，用户列表展示，用户新增，修改，删除，设置用户角色，用户删除头像，用户分为五种类型用户，管理员，采购员，采购经理，销售员，销售经理。

系统管理—角色维护，系统新增角色，支持富文本方式编辑。给角色添加对应的权限。

系统管理—菜单维护，新增系统菜单。一级菜单，二级菜单  菜单权限

系统管理-- 菜单维护，系统菜单图标，支持2000个以上的图标

系统管理—权限维护，权限列表维护，权限的新增 修改删除等操作

数据字典—系统通用数据维护，比较系统的商品品牌，商品的单位等信息

数据字典—字典类型新增，修改，删除，字典类型对应数据操作

数据字典—字典类型树的加载，点击字典类型，加载右侧数据

系统报表—展示商品销售的报表情况，图形的报表，很直观，好看

日志管理—无论何时何地都在记录系统的日志信息信息，你可以查看，搜索日志信息.

进货管理—采购商品的列表展示

进货管理-采购商品订单列超出，自动隐藏功能实现

进货管理-采购商品的高级添加搜索功能

进货管理-采购商品录入，弹出对话款，选择商品，自动加载对应的商品价格，商品品牌，商品单位。

进货管理—加载商品数据，加载供货商数据，加载采购员数据

进货管理-自动根据商品的数量，计算商品的采购总价

进货管理-商品的修改采购。修改只能针对 录入商品或者驳回商品进行修改，入库商品无法修改。

进货管理-商品的驳回功能，如果采购经理看到商品采购订单有问题，会打回商品信息，重新修改，在提交；

进货管理-商品清点入库功能，采购经理 核对商品的信息，准确无误之后，点击清点入库，进入库存。

进货管理-商品删除，只有录入或者驳回商品才能删除，已入库商品无法进行删除

进货管理-商品批量删除，可以批量删除商品

进货管理-采购流程图查看。

进货管理-菜单订单自动生成。

库存管理-商品库存列表分页展示

库存管理-商品库存列表高级查询

库存管理-商品库存列表预警效果提示

库存管理-商品采购入库之后，自动增加库存信息

库存管理-商品销售审核之后，自动扣减库存信息.

 

销售管理—销售商品订单的列表分页展示和高级查询

销售管理—销售商品订单列超出内容自动隐藏功能实现

销售管理-销售员对销售的商品录入，弹出对话框，选择商品，自动加载对应的商品价格，商品品牌，商品单位。

销售管理--加载商品数据，加载销售员的信息

销售管理-自动根据商品的数量，计算商品的销售总价

销售管理-销售商品库存量提示，不能销售大于库存量的商品。不能超出库存的上限。

销售管理--修改只能针对 录入商品或者驳回商品进行修改，入库商品无法修改。

销售管理-商品的驳回功能，如果销售经理看到商品已录入的销售订单有问题，会驳回商品信息，重新修改，在提交；

销售管理-商品审核入库功能，销售经理 核对商品的信息，准确无误之后，点击审核入库，进入库存。扣减库存

数据维护—维护商品的基本信息，商品的CRUD操作

数据维护—维护供货商的基本信息，供货商的CRUD操作

等等…………



系统设计文档：

![系统设计文档](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/%E6%96%87%E6%A1%A3%E6%88%AA%E5%9B%BE.png "在这里输入图片标题")



#### 核心流程图 

1.  采购流程图

![采购流程图](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/%E9%87%87%E8%B4%AD%E6%B5%81%E7%A8%8B.png "在这里输入图片标题")

2. 销售流程图

![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/%E9%94%80%E5%94%AE%E6%B5%81%E7%A8%8B.png "在这里输入图片标题")

#### 功能效果图展示

1登录
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/1%E7%99%BB%E5%BD%95.png "在这里输入图片标题")

2系统权限-用户列表
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/2系统权限-用户列表.png "在这里输入图片标题")

3新增用户
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/3新增用户.png "在这里输入图片标题")

4用户设置角色
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/4用户设置角色.png "在这里输入图片标题")

5角色模块
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/5角色模块.png "在这里输入图片标题")

6角色模块-新增角色
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/6角色模块-新增角色.png "在这里输入图片标题")

7菜单模块
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/7菜单模块.png "在这里输入图片标题")

8菜单模块-新增菜单
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/8菜单模块-新增菜单.png "在这里输入图片标题")

9数据字典
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/9数据字典.png "在这里输入图片标题")

10报表列表
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/10报表列表.png "在这里输入图片标题")

11系统日志
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/11系统日志.png "在这里输入图片标题")

12采购管理
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/12采购管理.png "在这里输入图片标题")

13新增采购订单
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/13新增采购订单.png "在这里输入图片标题")

14采购流程图
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/14采购流程图.png "在这里输入图片标题")

15销售单管理
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/15销售单管理.png "在这里输入图片标题")

16库存预警
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/16库存预警.png "在这里输入图片标题")

17商品维护
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/17商品维护.png "在这里输入图片标题")

18供货商维护
![输入图片说明](https://gitee.com/soul_PreCoder/itfxq_erp/raw/master/pic/18供货商维护.png "在这里输入图片标题")



#### 资料获取说明

需要获取资料+源码+视频的小伙伴 赶快加入 QQ2579692606  已经有很多人在学习的。

![输入图片说明](https://gitee.com/soul_PreCoder/lgapp/raw/master/img/qq%E4%BA%8C%E7%BB%B4%E7%A0%81.png "在这里输入图片标题")
