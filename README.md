<font style="color:#000000;">讯业软件开发/讯业明信片-java寄信写信系统</font>

### <font style="color:#000000;">一、产品概述</font>
**<font style="color:#000000;">往监狱里寄信的下单工具，线上写信，还能传照片，选信纸模板，买商品，选快递邮寄方式下单。</font>**

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214941612-16806174-e78c-4aa4-9585-01d08d6e6e52.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214954182-5de07775-4054-4ebb-b466-5eca3f88cd15.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214965330-71d8f9d0-1a37-49e8-8464-1cf4a504cf59.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214976107-d85628dd-a6ae-42af-9de7-1b6f7381c0f0.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214987260-f8f3f651-3bef-4eab-a6b1-a14af9287c5e.png)

<font style="color:#000000;"></font>

## <font style="color:#000000;">二、核心功能</font>
**<font style="color:#000000;">底部菜单栏：首页、商城、资讯、我的。  
</font>****<font style="color:#000000;">用户端小程序 用户可通过微信授权登录（获取头像、昵称、手机号）。</font>**

## <font style="color:#000000;">首页</font>
**<font style="color:#000000;">1，正常信件</font>****<font style="color:#000000;">：  
</font>****<font style="color:#000000;">步骤1：选择照片—可选择上传照片或无照片。  
</font>****<font style="color:#000000;">步骤2：填写信件—选择制作方式（线上写信/手写拍照/人工代写）。  
</font>****<font style="color:#000000;">线上写信：编辑信件内容。手写拍照：上传信件照片。人工代写：编辑信件内容。  
</font>****<font style="color:#000000;">步骤3：选择模板—模板风格选择，合成信件。  
</font>****<font style="color:#000000;">步骤4：购买商品—商城商品选择。  
</font>****<font style="color:#000000;">步骤5：确认支付—填写地址（收件地址、寄件地址）、发货时间、邮寄方式、支付方式（微信支付/余额支付/积分支付）、优惠券、费用信息明细展示。</font>**

**<font style="color:#000000;">2，明信片：</font>****<font style="color:#000000;">  
</font>****<font style="color:#000000;">选择制作方式（线上编辑/人工代写）线上编辑：选择图片–填写明信片内容（选择收件人，正文编写，署名）  
</font>****<font style="color:#000000;">人工代写：编辑信件内容。</font>**

**<font style="color:#000000;">  
</font>****<font style="color:#000000;">3，代收信件：</font>****<font style="color:#000000;">  
</font>****<font style="color:#000000;">下单时开启代收信，填写姓名手机号。  
</font>****<font style="color:#000000;">代收查询：有新的代收信件是可以在新信件查看。</font>**

**<font style="color:#000000;">  
</font>****<font style="color:#000000;">4，特色服务</font>****<font style="color:#000000;">：  
</font>****<font style="color:#000000;">充值立减：充值账户余额，可用于下单时余额支付，套餐不同套餐充值享不同折扣力度。  
</font>****<font style="color:#000000;">邀请有礼：邀请码保存分享好友。  
</font>****<font style="color:#000000;">回家倒计时：设置回家时间、离家时间。  
</font>****<font style="color:#000000;">日记存稿：编辑填写日记。</font>**

## <font style="color:#000000;">商城</font>
**<font style="color:#000000;">商品分类，商品信息展示，下单购买商品</font>**

## <font style="color:#000000;">资讯</font>
**<font style="color:#000000;">资讯文章列表，查看详情介绍。</font>**

## <font style="color:#000000;">我的</font>
**<font style="color:#000000;">小程序使用天数展示，累计寄出信件  
</font>****<font style="color:#000000;">订单：待付款、待制作、制作中、已寄出、已退款  
</font>****<font style="color:#000000;">签到有奖：每日签到随机得积分或谢谢参与。  
</font>****<font style="color:#000000;">优惠券：新人优惠券，邀请好友也得优惠券。</font>**

**<font style="color:#000000;"></font>**

## <font style="color:#000000;">架构特点</font>
### <font style="color:#000000;">架构特性</font>
+ **<font style="color:#000000;">前后端分离架构，独立开发，符合主流开发模式</font>**
+ **<font style="color:#000000;">前端以Vue3+Vite为主技术，AntdV为UI界面框架</font>**
+ **<font style="color:#000000;">后端SpringBoot3为基础，MybatisPlus为数据操作框架，Redis为缓存框架</font>**
+ **<font style="color:#000000;">Maven多模块管理，插件化开发，方便安装、卸载、升级，降低耦合</font>**
+ **<font style="color:#000000;">业务模块与API抽离，模块之间便捷引用</font>**
+ **<font style="color:#000000;">数据库设计精巧，字段规范、易于扩展</font>**
+ **<font style="color:#000000;">支持国产密码算法加解密，等保测评国产项目无压力</font>**
+ **<font style="color:#000000;">支持MYSQL、ORACLE、SQLSERVER、PGSQL等主流标准结构式数据库</font>**
+ **<font style="color:#000000;">支持达梦、人大金仓、南大通用、九有、瀚高、虚谷数据库等国产数据库</font>**
+ **<font style="color:#000000;">支持中创、宝蓝德、东方通等中间件</font>**
+ **<font style="color:#000000;">支持Windows、Linux操作系统、国产操作系统部署</font>**

### <font style="color:#000000;">功能特性</font>
+ **<font style="color:#000000;">完善的系统基础功能，满足使用需求，避免重复造轮子</font>**
+ **<font style="color:#000000;">支持本地文件、阿里云文件、腾讯云文件、MINIO文件上传</font>**
+ **<font style="color:#000000;">支持本地邮件、阿里云邮件、腾讯云邮件发送</font>**
+ **<font style="color:#000000;">支持阿里云短信、腾讯云短信发送</font>**
+ **<font style="color:#000000;">B、C端双账号认证体系，会话治理各自独立</font>**
+ **<font style="color:#000000;">完善的登录日志、操作日志、异常日志等审计功能</font>**
+ **<font style="color:#000000;">完善的会话监控、数据源监控、系统监控等必备监控功能</font>**
+ **<font style="color:#000000;">支持组织机构、权限管理、定时任务、系统配置等基础功能</font>**

### <font style="color:#000000;">安全特性</font>
+ **<font style="color:#000000;">采用SaToken轻量级 Java 权限认证框架，功能强大、学习成本低</font>**
+ **<font style="color:#000000;">支持登录认证、权限认证、单点登录、三方登录、OAuth2.0等认证模式</font>**
+ **<font style="color:#000000;">增强的RBAC权限设计，资源于接口独立授权，更加灵活</font>**
+ **<font style="color:#000000;">支持按钮级别细粒度独立授权，界面按钮动态展示</font>**
+ **<font style="color:#000000;">支持API接口注解式、路由拦截式鉴权，防止越界访问</font>**
+ **<font style="color:#000000;">独创的数据范围机制，每个接口都可以配置不同数据范围</font>**
+ **<font style="color:#000000;">支持限流防抖，防重复提交，有效阻止脏数据产生</font>**
+ **<font style="color:#000000;">密码、手机、身份证号等使用国密算法加密传输、加密存储，数据更安全</font>**
+ **<font style="color:#000000;">操作日志使用SM2进行完整性保护，满足安全审计要求</font>**

### <font style="color:#000000;">界面特性</font>
+ **<font style="color:#000000;">Vue3 + Vite为基础，AntdV为界面UI框架，视觉风格清新简洁</font>**
+ **<font style="color:#000000;">精细化设计，注重界面的每一处细节，操作轻松友好</font>**
+ **<font style="color:#000000;">暗黑风格、经典菜单、双排菜单、多页签、目录坞、主题切换等功能应有尽有</font>**
+ **<font style="color:#000000;">统一的网络框架、API接口拦截框架，拿来即可上手</font>**



**<font style="color:#000000;">联系交流</font>**

**<font style="color:#000000;">公司官网：</font>**[**https://www.xunyeit.com**](https://www.xunyeit.com)

**<font style="color:#000000;">案例库：</font>**[**https://cms.xunyeit.com/**](https://cms.xunyeit.com/)

**<font style="color:#000000;">交流微信：</font>**<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773215049522-637ebd3e-8649-4967-9897-bd54e9c0fdd6.png)

