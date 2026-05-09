# BSC OPC Agent OS V2.0

Amazon 产品运营 AI 助手 —— GPT-Image-2 图片生成 + COSMO/Rufus 算法 Listing 优化，一站式 Amazon 运营工具。

## 核心功能

### 🎨 产品图片生成
- **GPT-Image-2 图生图**：采集产品主图 → 自动抠图白底 → 融合知识库生成 10 种 Amazon 标准图片模板
- **模板覆盖**：白底主图、场景 lifestyle、A+ 品牌横幅、品牌故事卡、高清放大图、信息图、对比图、社交素材等
- **多服务商兼容**：支持 APIMart、等车等任意 OpenAI 兼容 GPT-Image-2 API

### 🧠 COSMO/Rufus 算法 Listing 优化
- **标题优化**：基于 COSMO 算法公式，自动分析原标题并生成中日英多语言优化版本
- **五点分析**：原始卖点 → 中文优化建议 → 站点语言翻译，含 COSMO 符合度评分
- **Rufus Q&A 建议**：8 维度结构化问答框架，自动翻译为站点语言 + 中文参考
- **卖点提炼**：SIF 关键词数据驱动，Top 3 核心卖点 + COSMO 强度评估
- **数据洞察**：市场信号监测（自然排名断档、广告依赖、关键词健康度）

### 📡 多源数据采集
- **SIF MCP**：关键词流量信号、排名趋势、流量占比
- **卖家精灵 / Sorftime MCP**：产品详情、销量、BSR、竞品数据（XOR 双通道互斥切换）
- **Amazon 页面采集**：实时抓取产品图片和五点描述

### 🖼️ 图片管理
- **批量采集**：输入 ASIN 自动抓取主图 + A+ 图片
- **智能抠图**：选中参考图自动去除背景生成白底产品图
- **参考图预览**：白底图/主图/A+ 图分类标记，点击设为原型
- **生成结果**：支持 PNG 下载和 PSD 导出

### 🔄 OTA 在线升级
- 自动检测 GitHub Release 最新版本
- 一键下载安装，保留用户配置和激活状态

### 🔐 软件激活
- 机器码绑定授权 / 3 天免费试用 / 激活后永久使用

## 技术特点
- 本地 Web 界面，浏览器操作，数据不出本地
- 自动识别 Amazon 站点语言（US/JP/DE/FR/IT/ES 等）
- MCP 协议集成：支持 SIF、卖家精灵、Sorftime 等 MCP 服务
- 内置 COSMO/Rufus 算法知识库

## 快速开始

### 系统要求
- Windows 10/11 64位
- 稳定的网络连接

### 安装步骤
1. 下载 `BSC-OPC-Agent.zip`，解压到任意目录
2. 运行 `BSC-OPC-Agent.exe`
3. 浏览器访问 `http://127.0.0.1:5173`
4. 在设置中配置 API 密钥
5. 输入 ASIN 开始使用

## V2.0 更新

### 新增
- GPT-Image-2 多服务商支持（APIMart/等车/任意 OpenAI 兼容 API）
- 卖家精灵 MCP 集成（与 Sorftime XOR 双通道切换）
- 白底抠图 + 图生图
- OTA 在线升级
- 提示词折叠分组
- 版本检测按钮

### 优化
- 设置面板 GPT-Image-2 通用化
- 结果图片 ASIN 隔离
- 采集速度提升
- Q&A 格式统一对齐
- VPN 检测逻辑优化

## 常见问题

**Q: 采集不到图片？** A: Amazon 对中国 IP 有限制，请开启 VPN 全局模式。

**Q: 生成图片失败？** A: 检查 Base URL 和 API Key 是否正确，余额是否充足。

**Q: 如何切换服务商？** A: 在设置中修改 Base URL 和 API Key 即可。

## 技术支持
- 微信公众号：商海蟹
- 知识星球：商海蟹
- GitHub Issues：https://github.com/luotwo/BSC-Amazon-OPC-Agent-OS/issues

---

**版权所有 © 商海蟹**
