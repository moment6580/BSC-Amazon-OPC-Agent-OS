# BSC OPC Agent OS 

Amazon 产品运营 AI 助手 —— GPT-Image-2 图片生成 + COSMO/Rufus 算法 Listing 优化，一站式 Amazon 运营工具。

## 实现案例

<img width="1536" height="1024" alt="5a51c41b4820c65d099b3c096ec16f37" src="https://github.com/user-attachments/assets/422749be-cfbc-4480-b6a4-b3a051b43fd6" />
<img width="1536" height="1024" alt="206cd21f1dee1b3b008d110c6b6e18cf" src="https://github.com/user-attachments/assets/10db0075-8fcf-4a02-8687-095df64edf24" />
<img width="1970" height="1264" alt="fc7f019b9678ccdca1403123c7ecc882" src="https://github.com/user-attachments/assets/d11d43f8-3449-4b9e-b2ac-c13b69a8a7ad" />
<img width="1951" height="1280" alt="1a73fa60d7cbacdc1973fcd0eaa21bb3" src="https://github.com/user-attachments/assets/5991fa6d-059b-4ecf-9c52-a53e6d8b3a7a" />
<img width="1937" height="1280" alt="ba0aa23968deffc86912c6a35fd26aad" src="https://github.com/user-attachments/assets/fc298c55-79d4-42c7-9688-b36f6ecc8b76" />
<img width="1952" height="1280" alt="8a84a1c8e98b3fddc331b37569755fbb" src="https://github.com/user-attachments/assets/ec0d7974-bb67-4694-8c92-d2a943236603" />
<img width="1924" height="1280" alt="e3a6b1fe50fa8a57e0aa8f236e499c3d" src="https://github.com/user-attachments/assets/f61d09d8-b46c-446d-8971-dd30da799777" />
<img width="1944" height="1280" alt="4670698d2d98975db486855fd9ec5c25" src="https://github.com/user-attachments/assets/0e3d412b-dd31-4372-8ea2-3312b18b28dd" />
<img width="1951" height="1280" alt="6a7de5ee20bb308deef561a801a489ea" src="https://github.com/user-attachments/assets/067c851d-12e6-4103-b55d-78b611a2c7ac" />



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
<img width="1774" height="887" alt="9ecebe29f171c255686c0719c4e69119" src="https://github.com/user-attachments/assets/cf0b5bc6-f5bf-4d9f-ac6a-c5e85cf09685" />

---
<img width="1254" height="1254" alt="未命名" src="https://github.com/user-attachments/assets/dad1217b-e17a-4f1d-9323-7ea8d9854652" />

**版权所有 © 商海蟹**

## V2.2 更新 (2026-05-11)

### 新增
- **自动抠图**：选中任意产品图（场景图/主图），一键完成白底提取并生成对应风格图片，无需手动上传白底图
- **图生图速度优化**：提示词生成阶段提速 85%（批量翻译合并，耗时大幅缩短）

### 修复
- MCP 连接修复：设置页各 MCP 服务（SIF / Sorftime / 卖家精灵）连接测试回归正常
- 设置页面部分选项状态保存错误
- OpenAI 兼容服务（GPT-Image-2）轮询检测逻辑

### 体验优化
- 未选图时点击生成会明确提示"请先选择产品主图"
- 主页偶发无法打开的问题已修复
