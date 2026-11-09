<div align="center">

# n8n 社区节点开发工作空间

连接业务应用，让自动化更进一步。

**简体中文** | [English](https://github.com/luka-n8n-nodes/.github/blob/main/profile/README.en.md)

</div>

---

## 📦 关于本仓库

本仓库用于开发和维护 N8N 社区节点插件。插件主要采用 TypeScript 开发，遵循 N8N 社区节点的开发规范和最佳实践。

## 🎯 仓库目录

本组织全部 18 个公开仓库按用途分类如下，包含 17 个 n8n 插件及 1 个组织主页仓库。点击仓库名称查看文档与使用说明。

核对日期：2026-11-09 · [浏览全部仓库](https://github.com/orgs/luka-n8n-nodes/repositories)

### 协作与流程自动化

| 仓库 | 简介 |
| --- | --- |
| [n8n-nodes-feishu](https://github.com/luka-n8n-nodes/n8n-nodes-feishu) | **双模式事件驱动与多维表格增强**：支持 WebSocket / Webhook 监听及同步事件响应；提供字段映射、条件分支和 Upsert。覆盖文档、知识库、消息、日历等场景，并内置自动分页、批次控制与大文件分片上传。 |
| [n8n-nodes-feishu-project](https://github.com/luka-n8n-nodes/n8n-nodes-feishu-project) | **可视化配置项目自动化**：覆盖工作项、流程节点、视图、评论及附件；动态加载空间和工作项类型，减少手填参数。支持自动分页、批次处理和超时控制，便于跨系统同步项目数据。 |
| [n8n-nodes-qingflow-oa](https://github.com/luka-n8n-nodes/n8n-nodes-qingflow-oa) | **从通讯录同步到审批流程操作**：管理成员、部门、角色、应用及表单数据，支持处理、催办、重新指派、回退和任务委托。内置自动分页，并在检测到 Token 过期时刷新凭证、重试请求。 |
| [n8n-nodes-yingdao-rpa](https://github.com/luka-n8n-nodes/n8n-nodes-yingdao-rpa) | **启动机器人并等待执行结果**：Job 启动后可暂停 n8n 工作流，收到影刀回调再自动恢复，无需另接 Wait 节点。还可管理机器人分组、任务重试、运行日志和工作队列，串联 API 与桌面 RPA 自动化。 |
| [n8n-nodes-browserless](https://github.com/luka-n8n-nodes/n8n-nodes-browserless) | **网页数据与文件一站式处理**：基于 Browserless API V2，支持渲染后 HTML、结构化抓取、截图、PDF、自定义脚本及下载。可作为 AI Agent 工具使用；PDF 和下载支持文件名、MIME 类型等输出配置。 |

### 人力资源与企业管理

| 仓库 | 简介 |
| --- | --- |
| [n8n-nodes-moka-people](https://github.com/luka-n8n-nodes/n8n-nodes-moka-people) | **人事数据同步与 BI 报表转换**：支持员工新增、更新、批量附件、基本信息回写及组织部门维护。BI 报表可按表头名称输出独立 n8n 数据项，并支持多级表头，减少后续字段整理工作。 |
| [n8n-nodes-mokahr](https://github.com/luka-n8n-nodes/n8n-nodes-mokahr) | **招聘全阶段数据获取**：覆盖候选人、简历解析文本、附件、标签、评价表及人才库，支持中国版和国际版。提供游标分页，部分查询可从上次游标继续，并支持批次节奏及并发输入控制。 |
| [n8n-nodes-italent](https://github.com/luka-n8n-nodes/n8n-nodes-italent) | **聚焦北森 AI 面试自动化**：支持发起或取消面试、获取邀请链接、作答结果、应聘者及活动数据。按接口校验邀请 ID 数量限制，支持表达式数组、自动分页和批次间隔，便于串联面试通知与结果回收。 |
| [n8n-nodes-kingdee](https://github.com/luka-n8n-nodes/n8n-nodes-kingdee) | **覆盖 47 类 ERP 业务资源**：连接基础资料、财务、采购、销售、库存、生产、质量及税务数据；按资源支持单据保存、提交、审核和批量操作。内置应用授权、Cookie 会话管理及日期、多语言字段处理。 |
| [n8n-nodes-didi-enterprise-admin](https://github.com/luka-n8n-nodes/n8n-nodes-didi-enterprise-admin) | **企业出行组织与人员同步**：管理部门、项目、员工及项目人员关系。自动处理授权、请求签名和 AES 加密；查询支持自动分页，写操作默认按 150 毫秒间隔限速，减少手工对接鉴权与频控的工作。 |

### 身份、安全与云服务

| 仓库 | 简介 |
| --- | --- |
| [n8n-nodes-authing-admin](https://github.com/luka-n8n-nodes/n8n-nodes-authing-admin) | **身份管理与账号生命周期自动化**：涵盖用户、用户组、组织部门、公共账号及自定义域名，支持用户离职和域名归属验证。用户组动态下拉减少手填 Code；可通过自定义请求扩展调用其他 Admin API。 |
| [n8n-nodes-feilian](https://github.com/luka-n8n-nodes/n8n-nodes-feilian) | **事件驱动的 IT 与终端管理**：Webhook 自动完成 URL 验证，可校验 Token、解密推送并过滤事件。覆盖人员角色、Wi-Fi 日志、终端设备、软件使用及许可证授权，并支持递归部门成员查询和自动分页。 |
| [n8n-nodes-volcengine](https://github.com/luka-n8n-nodes/n8n-nodes-volcengine) | **知识库 AI 与云端身份管理结合**：支持 VikingDB 知识库语义检索、基于多种豆包模型的多轮对话，以及 IAM 用户和登录配置管理。自定义请求支持 GET/POST、Query 与 Body 参数，可扩展调用火山引擎 OpenAPI。 |
| [n8n-nodes-pgp](https://github.com/luka-n8n-nodes/n8n-nodes-pgp) | **文本与文件的 OpenPGP 加密签名**：提供加密、解密、签名、验签及两种组合操作，支持二进制文件、嵌入式签名和压缩。可将“加密并签名”或“解密并验签”合并为一步，适合文件交换流程。 |
| [n8n-nodes-bcryptjs](https://github.com/luka-n8n-nodes/n8n-nodes-bcryptjs) | **密码哈希之外的完整校验工具**：支持异步生成哈希、密码比对、生成盐值、提取盐值与计算轮数，并检测超过 72 字节导致的截断。可配置计算成本和输出字段，便于接入账号创建、验证与检查流程。 |

### 开发与文件处理工具

| 仓库 | 简介 |
| --- | --- |
| [n8n-nodes-semver](https://github.com/luka-n8n-nodes/n8n-nodes-semver) | **从版本校验到发布决策**：封装版本解析、比较、范围匹配、递增、清理、转换与排序。可查找满足依赖范围的最高或最低版本，处理预发布版本，用于依赖兼容检查和发布版本号自动生成。 |
| [n8n-nodes-heic-convert](https://github.com/luka-n8n-nodes/n8n-nodes-heic-convert) | **面向工作流的批量图片转换**：将 HEIC/HEIF 转为 PNG 或 JPEG，支持 JPEG 质量调节、自定义输入输出二进制字段，并保留原文件名、更新扩展名。单张失败时可按配置继续处理其他图片。 |

### 组织主页

| 仓库 | 简介 |
| --- | --- |
| [.github](https://github.com/luka-n8n-nodes/.github) | **组织项目的双语导航入口**：默认中文，支持中英文双向切换；按业务用途汇总全部公开仓库，集中展示插件特点、项目链接与开发规范，帮助快速找到适合的集成工具。 |

## 🛠️ 技术栈

- **TypeScript** - 类型安全的开发体验
- **N8N** - 工作流自动化平台
- **Node.js** - 运行时环境

## 📝 开发规范

所有插件遵循以下开发规范：

- 使用 TypeScript 进行开发
- 遵循 N8N 社区节点的代码结构
- 提供完整的类型定义
- 完善的错误处理和用户提示
- 统一的参数设计

## 🔗 相关链接

- [N8N 官方文档](https://docs.n8n.io/)
- [N8N 社区节点开发指南](https://docs.n8n.io/integrations/community-nodes/)


---

[切换至英文 / English](https://github.com/luka-n8n-nodes/.github/blob/main/profile/README.en.md)
