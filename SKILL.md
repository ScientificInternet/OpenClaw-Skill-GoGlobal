---
name: GoGlobal
slug: GoGlobal
version: 1.3.0
description: "出海基础设施搭建助手。引导用户从购买服务器到连上外网，全程不碰技术。支持搬瓦工KiwiVM API零SSH自动部署。"
author: ScientificInternet
tags: [cross-border, infrastructure, vps, deployment, proxy]
---

# GoGlobal — 出海基础设施一键搭建

零基础用户从买服务器到连上外网的完整引导。

## 能做什么

1. 引导购买服务器（推荐搬瓦工）
2. 通过KiwiVM API自动部署（用户不碰SSH）
3. 安装3x-ui管理面板并配置节点
4. 引导手机/电脑安装客户端（iOS/Android/Windows/Mac）
5. 内置常见问题诊断

## 面向谁

完全不懂技术的新手。需要访问Google、Meta、TikTok、ChatGPT、Claude做跨境生意的人。

## 怎么用

用户粘贴搬瓦工的一行CSV → agent通过API自动部署 → 用户在面板里点几下创建节点 → 手机扫码连上 → 完事。

## 需要什么

- 搬瓦工服务器（推荐$20/月 ECOMMERCE SLA）
- 浏览器
- 手机或电脑装客户端

## 安全说明

- 用户的KiwiVM API Key仅能操作其自己的VPS，不涉及支付或账户凭证
- 所有破坏性操作（重装系统）均带数据丢失警告
- 面板凭据从安装日志提取后，引导用户修改默认密码
- 防火墙故障排查采用端口放行而非全局关闭
- 安装脚本来源为GitHub开源仓库（MHSanaei/3x-ui）
