


### 部署注意事项
如果自行升级版本时，请先备份好数据，防止新版本结构变化，关联数据无法找回。
### 项目概述
无忧企业文档主要服务客群为企业用户，解决企业内部文档编辑、知识沉淀、知识协同等痛点。
项目主要采用Java开发，基础框架采用JVS（spring cloud+Vue）。
适用场景：
适用于个人、团队、企业使用，提供云笔记、个人知识沉淀、在线产品手册、团队内部知识库、在线电子教程等功能。
支持SaaS模式，支持私有化部署场景。

### 特性

* 富文本
* 脑图
* 流程图
* excel
* 编辑/查看权限 
* 协同人员设置 
* 评论
* 点赞
* 搜索

***
### 基础能力：

- 多模式用户登录，微信登陆、账号密码登录;
- 采用前台应用+后台管理的模式
- 具备后台组织管理、用户账号密码管理、角色权限管理
- 基础框架采用JVS（spring cloud alibaba的衍生版本）的微服务框架
- 内容划分：采用分类、聚合等方式，形成文档集或者知识库
- 支持本地化部署；权限化管理，有效的信息分级控制
- B/S模式，不依赖与客户端，数据私有云或者公有云存储
- 能对分享的范围进行控制，可以对分享的时间有效性、支持密码、内部账号等
- 无人数限制，支持商用、支持内部自用，使用成本低
- 代码支持完全开源，容易扩展，采用Java语言开发，提供便捷的二开技术支持
- 基础框架支持微服务，支持海量并发
- 支持多租户，支持云台运营场景

### 文集（知识库）管理

- 全站智能搜索引擎，支持文档级、内容级检索
- 文集的增删改查
- 文集的团队成员协作（可查看、可编辑）
- 文集的目录结构化管理
- 文集的基础介绍
- 知识库的参与协作人员
- 支持多种角色协同（成员、管理者、所有者）

### 个人文档管理：

- 支持富文本（类word）、脑图（类Xmind）、流程图（类viso）
- 文档的增删改查、文档在线编辑
- 文本大纲，小标题导航
- 支持所见即所得
- 支持在线表格表格
- 支持图片、表格、三方应用、音频、视频、等富文本表达插件
- 支持预览、全屏、打印等扩展组件
- 支持代码块、引用、
- 支持源代码查看


### 项目组成
企业文档分为业务前台与管理后台，项目由 业务前台与管理后台组成

业务前台前端地址：https://github.com/RKQF-JVS/jvs-knowledge-ui

业务前台后端地址：https://github.com/RKQF-JVS/jvs-apply-document

管理后台前端地址：https://github.com/RKQF-JVS/jvs-ui

管理后台后端地址：https://github.com/RKQF-JVS/jvs


### 演示地址
演示地址：http://knowledge.bctools.cn/

试用账号：微信扫码即可登陆，如需要账号密码试用，请二维码联系我们


### 技术栈说明
* JVS+VUE
* Spring Cloud Alibaba
* VUE+Element UI

### 使用与授权
无忧企业文档采用100%开源模式，在合规备案情况下，支持自用与商用，商用提供100%源代码。
### 版本说明：
使用用途|费用模式|使用条件|授权时间
-|-|-|-
个人学习、个人使用|免费|免费备案|永久
商用、二次开发|收费、代码交付|技术服务合同+商用备案|永久

### 商用费用说明：
- > 技术服务费，必选，具体费用请与商务沟通
- > 定制开发费，可选，1500元/人天
- > 部署费用，可选，500元/次
- > 长期运维，可选，协商


备案说明：联系我们的商务人员，在线备案，备案内容：项目名称，使用模式（自用/商用），备案主体主体，备案联系人员，即可。
### 禁止行为（为了保障产品走得更远）：
* 在未获得我方认可分发代码的情况下，禁止以任何形式进行代码分发（包含但不限于代码拷贝、代码公开、代码开源、代码分享等行为）
* 禁止在未备案的情况下，私自使用（包含自用与商用）


### 技术交流与商务支持

![image](https://user-images.githubusercontent.com/94048608/187455164-79f5cfaa-5056-4703-bada-87fb0e68e0be.png)
### 版本规划：
V1.5

* 支持多人在线同时协同编辑
* 优化画图功能
* 文档知识库分享
* 模板管理
* 接入WPS

### 历史更新记录：
V1.3  20211202 

* 修改部分UI展示图
* 添加多种文件格式在线预览
* 添加软件介绍页
* 添加当前租户下与组织内人员查看
* 添加知识库背景替换
* 修复部分BUG
