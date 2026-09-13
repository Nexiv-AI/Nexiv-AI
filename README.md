
# Nexiv AI

<div align="center">

> 原 ArtDraw‑AI · **一站式 AI 绘图聚合平台**

> **平台简介**  
> Nexiv AI 聚合 OpenAI / Midjourney / Google / Flux / Kling / 豆包 / Grok 等顶级 AI 绘图模型，统一计费、一键调用。  
> 关键词：AI 绘图,AI 画图,Midjourney,DALL·E,FLUX,Nano Banana,Kling,Seedream,文生图,API
</div>

<!-- Logo 占位 -->
<p align="center">
  <img src="./dist/logo.png" alt="Nexiv AI Logo" width="200" />
</p>


## 🔗 官方链接

| 服务 | 地址 | 说明 |
|---|---|---|
| 🚀 演示站点 | https://demo.nexiv.me | 网页演示站 |
| 🛡️ 授权站点 1 | https://nexivai_auth.nexiv.me | 授权管理平台 |
| 🛡️ 授权站点 2 | https://artdraw-auth.l11.top | 备用授权平台 |
| 📊 运营后台 | https://nexiv.me | 运营管理后台 |
| 📖 文档站点 | https://docs.nexiv.me | 使用文档 |

> 后台测试账号：
> - 账号：`nexivai`
> - 密码：`123123`

---

<!-- 控制台预览占位 -->
![Dashboard Preview](./dist/dashboard.png)

## ✨ 核心功能

### 💬 AI 对话与智能体

- 多模型接入（GPT / Claude / Gemini / DeepSeek / 豆包 等）
- 兼容 OpenAI Responses API
- 原生智能体，支持 MCP 协议与技能插件
- 智能体工具池管理
- 智能体规划模型独立配置
- 绘图、视频工具可单独指定模型
- 会话分组、会话置顶、生成重试
- 对话时间线浏览
- 全局快捷键（Ctrl+K 全局搜索）
- 增强版 Markdown 渲染器
- 对话内可视化组件：思维导图 · 流程图 · 拓扑图 · 结构图 · 时间线

<!-- 智能体预览占位 -->
![Agent Preview](./dist/agent.png)

### 🔍 私有化 AI 搜索

- 多搜索引擎支持：Tavily、Meta‑So，多密钥轮询
- 网页 · 图片 · 文档 · Github · 新闻 · 学术文献检索
- AI 自动生成搜索关键词
- 网页深度阅读，自动过滤广告
- 搜索结果自动去重与质量筛选
- 可视化实时搜索进度面板
- 带编号来源引用标注
- 可单独开关每个搜索工具，自定义搜索参数
- 搜索工具独立点数计费

<!-- AI 搜索预览占位 -->
![AI Search Preview](./dist/search.png)

### 🎨 AI 创作套件

**AI 绘图**

- 多厂商绘图适配器，聚合 OpenAI / Midjourney / Google / Flux / Kling / 豆包 / Grok 等模型
- 支持参考图、局部重绘、蒙版、复刻风格
- 批量生成图片；后端自动对不兼容服务商拆分请求
- 五种创作布局；节点画布工作流
- 提示词预设库，分组管理
- 社区作品画廊，支持投稿与审核流程
- 
![AI Creation Preview](./dist/chuangzuo.png)
**AI 视频**

- AI 视频生成；可在智能体工作流内调用

**AI‑PPT（自研，非第三方 API）**

- 上传自定义 PPTX 模板
- 可视化配置可替换图文占位；自动填充幻灯片

<!-- 创作预览占位 -->
![AI Creation Preview](./dist/creation.png)
![AI Creation Preview](./dist/creation2.png)
### 💻 在线 IDE 与容器工作空间

- 浏览器内置 IDE，支持实时预览
- 双预览路由：子域名预览 + 备用路径预览
- 完整容器生命周期管理：创建 / 启动 / 停止 / 销毁
- CPU、内存实时指标监控
- 两种计费模式：内存套餐计费、运行时长计费
- 用户项目可绑定自定义域名
- 多模式域名所有权验证
- 自动申请 SSL 证书与反向代理配置
- 运维面板集成：堡塔面板、1Panel
- 可视化系统初始化，**无需手动编辑 .env 文件**
- 拖拽上传文件，剪贴板粘贴上传


### 💰 模型管理与商业化

- 模型封面图/视频上传
- 内置模板，AI 批量生成模型封面
- 模型健康监控：调用量、失败率、成功率、用户评分
- 14 天调用趋势图表
- 可视化模型选择器与独立模型详情页
- 后台可编辑模型元数据与标签
- 高精度点数系统，支持 8 位小数
- 细粒度计费：每个模型、每个子动作独立计费，智能体工具单独扣点
- 自定义充值套餐；多支付网关接入
- 批量兑换码管理
- 用户账单与交易记录

<!-- 模型管理预览占位 -->
![Model Management Preview](./dist/model.png)

### 🔐 账号与授权系统

- 账号密码登录、邮箱登录、手机号登录
- 微信公众号登录、QQ 聚合登录
- 账号安全中心，第三方账号绑定，自助重置密码
- 多节点商业授权系统
- 离线授权支持，可隔离内网部署
- www 子域名自动授权
- RBAC 权限：管理员角色 & 普通用户角色
- JWT 身份认证，预检请求拦截未授权访问

### 📝 反馈跟踪系统

- 在线提交 Bug 和功能需求
- 支持图片/视频附件
- 完整状态流转：已接收 → 处理中(%) → 已完成 → 待发布 → 已发布
- 状态变更邮件通知提交人

### 🖥️ 桌面客户端

- Tauri‑Rust Windows 桌面客户端
- 桌面专属智能体本地工作空间模式：本地文件读写 & Shell 执行
- 独立桌面设置面板与公告系统
- 二维码登录 & 网页跳转授权登录

### 🤖 微信 ClawBot

- 微信 ClawBot 机器人集成
- 通过微信机器人调用智能体、MCP、绘图、视频生成、对话、定时任务

### 🌏 UI 定制与国际化

- 全局页面过渡动画，图片懒加载动画
- 通用图片灯箱查看器；画廊分类管理
- 多语言：简体中文 · 英文 · 日文 · 韩文，后台批量翻译
- 全局背景自定义：网格、点阵、涟漪动画背景；自定义图片/视频背景
- 全局字体选择器
- 静态页面 Markdown 可视化编辑器：服务条款、隐私政策、常见问题、关于我们

### 🛠️ 运维能力

- 双存储后端：本地存储 & S3 兼容对象存储
- API 服务商多密钥轮询，自动故障转移
- 一键数据库表结构同步
- 运维大盘
- 验证码服务商：极验 v4、Cloudflare Turnstile

### 🧩 其他功能

- 语音输入（ASR）
- OpenAI TTS 语音播报，可自定义音色配置
- 邀请返利体系
- 全局吉祥物自定义：颜色、姿态、配饰、主题

---

## 🧱 技术栈

| 分层 | 技术 |
|---|---|
| 前端 | React + TypeScript + Vite + TailwindCSS |
| 后端 | Golang |
| 桌面客户端 | Tauri + Rust |
| 数据库 | MySQL + Redis |
| 部署方式 | Go服务 / Docker Compose |

---

## 界面截图

<details>
<summary>前端界面（17 张，点击展开）</summary>

![前端界面 01](./dist/frontend-01.png)

![前端界面 02](./dist/frontend-02.png)

![前端界面 03](./dist/frontend-03.png)

![前端界面 04](./dist/frontend-04.png)

![前端界面 05](./dist/frontend-05.png)

![前端界面 06](./dist/frontend-06.png)

![前端界面 07](./dist/frontend-07.png)

![前端界面 08](./dist/frontend-08.png)

![前端界面 09](./dist/frontend-09.png)

![前端界面 10](./dist/frontend-10.png)

![前端界面 11](./dist/frontend-11.png)

![前端界面 12](./dist/frontend-12.png)

![前端界面 13](./dist/frontend-13.png)

![前端界面 14](./dist/frontend-14.png)

![前端界面 15](./dist/frontend-15.png)

![前端界面 16](./dist/frontend-16.png)

![前端界面 17](./dist/frontend-17.png)

</details>

<details>
<summary>后台界面（13 张，点击展开）</summary>

![后台界面 01](./dist/admin/admin-01.png)

![后台界面 02](./dist/admin/admin-02.png)

![后台界面 03](./dist/admin/admin-03.png)

![后台界面 04](./dist/admin/admin-04.png)

![后台界面 05](./dist/admin/admin-05.png)

![后台界面 06](./dist/admin/admin-06.png)

![后台界面 07](./dist/admin/admin-07.png)

![后台界面 08](./dist/admin/admin-08.png)

![后台界面 09](./dist/admin/admin-09.png)

![后台界面 10](./dist/admin/admin-10.png)

![后台界面 11](./dist/admin/admin-11.png)

![后台界面 12](./dist/admin/admin-12.png)

![后台界面 13](./dist/admin/admin-13.png)

</details>
