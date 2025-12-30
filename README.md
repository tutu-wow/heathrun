# heathrun
个人运动打卡小程序 计算机毕业设计

所有源码均本人开发，项目是前后端分离的，所有的项目都具备了完整的业务逻辑，不仅仅局限于基础的增删改查（CRUD）操作，系统亮点众多。

本文注重于计算机毕业设计选题指导，列出题目均有源码， 大家可以去【公众号】(毕业终点站)获取或者加我【qq】(2112698948)提意见(别忘记Star哟)。备注：git

声明：仅用于学习使用，请勿用于任何商业行为！

1.系统非商用，非开源，非无偿。

2.由本人开发，如需源码，请联系以下方式，qq:2112698948。

3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。

<font style="color:rgb(17, 124, 238);">🎈</font><font style="color:rgb(17, 124, 238);">系统亮点：WebSocket实时通讯、快递物流API、Echarts图形化分析；</font>

# <font style="color:rgb(72, 179, 120);">一.系统开发工具与环境搭建</font>
## <font style="color:rgb(38, 38, 38);">1.系统设计开发工具</font>
<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">后端使用Java编程语言的Spring boot框架</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">项目架构：B/S架构</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">运行环境：win10/win11、jdk17</font>

<font style="color:rgb(38, 38, 38);"></font>

<font style="color:rgb(72, 179, 120);">小程序：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：Uniapp；UI库：ColorUI；   
</font><font style="color:rgb(38, 38, 38);">开发工具：HBuilderX；</font>

---

<font style="color:rgb(38, 38, 38);"></font><font style="color:rgb(72, 179, 120);">前端：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：框架Vue.js；UI库：ElementUI；   
</font><font style="color:rgb(38, 38, 38);">开发工具：Visual Studio Code；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">后端:</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：Java语言、mybatis plus、Spring boot框架；   
</font><font style="color:rgb(38, 38, 38);">开发工具：IDEA 2024版本；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">数据库：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库：mysql5.7/8.0 </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库工具：Navicat12版本；</font>

---

# <font style="color:rgb(72, 179, 120);">二.系统实现（部分截图）</font>
## 2.1 用户
### 2.1.1 首页
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077234192-2a40d894-120a-4562-9f61-64f625db7f4e.png)

### 2.1.2 正常健走
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077245004-65cd579e-382e-42d1-86b1-2b3a4fd1cde2.png)

### 2.1.3 健步活动
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077249620-5374853d-214a-43bd-9952-26792411971b.png)

### 2.1.4话题论坛
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077255038-d62957db-317e-4499-bfc6-912c6acd7724.png)

### 2.1.5 个人中心
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077259790-a0cc00ed-8fe7-46c1-83cb-007e2e0e3888.png)

## 2.2 管理员
### 2.2.1 综合分析
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077268734-e87a81c8-1237-45d9-9469-5328c2f95599.png)

### 2.2.2 用户信息
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077271284-526ad854-67f3-4dcf-8d12-47fda73477f6.png)

### 2.2.3 活动信息
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077275499-f16bf0ec-e167-430c-8d84-b039d9b01b62.png)

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077278940-43d478e9-4df0-4685-be5a-e98fafb27e15.png)

### 2.2.4 活动登记
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077283527-fde3375e-d13e-49c2-a2dc-e012fe56aae7.png)

### 2.2.5 数据分析
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077288724-82295895-95ac-4817-bb7c-a9351424e500.png)

### 2.2.6 话题信息
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077328666-3dc816e6-f114-4015-9751-0fc562486ae2.png)

### 2.2.7 系统通知
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077334088-ed76ce94-d6c4-41d6-8872-f2cf4e6f4807.png)

### 2.2.8 运动记录
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077337199-09d92a2a-b45f-42f2-bf84-9f35d9c2e39b.png)

# <font style="color:rgb(72, 179, 120);">三、系统代码结构截图</font>
## <font style="color:rgb(38, 38, 38);">3.1 前端</font>
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077340812-e257d6b5-26c6-4dd2-be62-12a4ba55d2db.png)

## <font style="color:rgb(38, 38, 38);">3.2 后端</font>
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077343016-e3853b65-e679-4166-83c9-cccf1f28fec7.png)

## <font style="color:rgb(38, 38, 38);">3.3 小程序</font>
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077346258-177837ce-dd74-4948-8f85-445cd659da0d.png)

## <font style="color:rgb(38, 38, 38);">3.4 数据库</font>
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1767077349080-284c9242-3437-4417-b80b-d78e917fb53a.png)

# <font style="color:rgb(72, 179, 120);">四.</font><font style="color:rgb(26, 173, 25);">系统源码获取</font>
<font style="color:rgb(0, 0, 0);">1.系统非商用，非开源，非无偿。</font>

<font style="color:rgb(0, 0, 0);">2.由本人开发，非简单增删改查操作，业务逻辑完整。</font>

<font style="color:rgb(0, 0, 0);">3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。</font>

