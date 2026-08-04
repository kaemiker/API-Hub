# AS Router
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[English Document](./README_EN.md) |

## 📌 项目介绍
**AS Router** 一站式API聚合中转平台，统一接口调用多家主流大模型，无需切换不同服务商密钥，简化开发接入流程。

## ✨ 核心功能
单网关聚合大量第三方 API 接口
- 统一 API‑Key 鉴权管理
- 请求转发、参数格式自动适配
- 调用日志、流量与用量统计面板
- 支持标准 HTTP/HTTPS 请求

## ✨ 支持模型列表
平台现已接入主流大模型：
- Moonshot（月之暗面）
- ChatGLM（智谱AI）
- Doubao（豆包）
- DeepSeek
- Qwen（通义千问）
- 元宝（MiniMax）

后续将会持续扩充更多AI模型接口。

## 🎁 新人福利
新用户注册账号，即可领取 **15美元通用优惠券**，可用于抵扣模型调用费用。

## 🚀 快速开始
1. 前往官网：`https://asrouter.com`
2. 注册账号，领取新人优惠券
3. 创建API Key
4. 使用统一接口地址对接各类大模型

## 💡 调用示例
```curl
curl https://asrouter.com/v1/chat/completions \
  -H "Authorization: Bearer 你的API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "doubao-pro",
    "messages": [{"role": "user", "content": "你好"}]
  }'
⚠️ 免责声明
本平台仅提供 API 转发聚合服务，各 AI 模型版权归属对应的模型厂商；
用户通过本平台生成的内容，由用户自行承担全部法律责任；
禁止利用本服务从事违法、违规、侵权类相关活动；
优惠券活动规则最终以平台官网公示为准，平台保留活动调整权利。

📮 交流与反馈
如有使用问题、功能建议，可以在 Discussions 发起讨论。
