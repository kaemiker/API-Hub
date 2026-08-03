# API-Hub - All-in-one API Aggregator

[![Online Service](https://img.shields.io/badge/Online-Service-asrouter.com-blue)](https://asrouter.com)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)

> 🌏 Language：English | [简体中文](./README_zh.md)

## 📖 Introduction
API-Hub is a unified API aggregation platform.
It integrates multiple third-party services, provides standardized request entry, unified authentication and request forwarding, greatly lowering the development cost when calling different external interfaces.

This repository stores SDK examples, demo codes and usage guides.
**Official Platform: https://asrouter.com**

## ✨ Core Features
- Single gateway to aggregate massive third-party APIs
- Unified API key authentication management
- Request forwarding, parameter format adaptation
- Call logs, traffic & usage statistics dashboard
- Standard HTTP/HTTPS request support

## 🚀 Quick Start Example
### cURL
```bash
curl "https://asrouter.com/api/v1/demo" \
-H "Authorization: Bearer YOUR_API_KEY"
