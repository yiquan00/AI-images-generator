# AI 图像生成系统

## 网站：
- [colorfun](https://colorfun.cc) 

## 项目概述

这是一个基于 Next.js 和 TypeScript 的全栈应用，主要功能是生成和管理 AI 图像。系统包括用户管理、图像生成、支付集成等功能。

## 主要功能

1. 用户管理：注册、登录、个人信息管理
2. 图像生成：使用 AI 模型生成自定义图像
3. 支付系统：集成 Stripe 支付功能，支持一次性支付和订阅模式
4. 积分系统：用户可以购买积分来生成图像
5. 图片处理：上传、展示和下载图像
6. 分类和标签系统：对图像进行分类和标签管理

## 技术栈

- 前端框架：Next.js（使用 App Router）
- 编程语言：TypeScript
- 数据库：PostgreSQL（使用 pg 库进行连接）
- 样式：Tailwind CSS
- 状态管理：React Hooks
- 身份验证：Clerk
- 支付集成：Stripe
- 图片处理：Cloudflare R2
- AI 模型集成：Replicate API
- 谷歌分析集成：Google Analytics

## 主要组件和模块

1. 用户组件 (User Component)：
```typescript:components/user/index.tsx
startLine: 1
endLine: 58
```

2. 定价页面 (Pricing Page)：
```typescript:app/(default)/pricing/page.tsx
startLine: 1
endLine: 203
```

3. 支付处理 (Checkout API)：
```typescript:app/api/checkout/route.ts
startLine: 1
endLine: 112
```

4. 图像生成 API：
```typescript:app/api/gen-cover/route.ts
startLine: 1
endLine: 86
```

## 样式

项目使用 Tailwind CSS 进行样式管理，主要样式定义在：
```css:.next/static/css/app/layout.css
startLine: 1
endLine: 500
```

## 开发指南

1. 克隆项目到本地
2. 安装依赖：`yarn install`
3. 设置环境变量（参考 `.env.example` 文件）
4. 运行开发服务器：`yarn dev`

## 部署

项目可以部署到 netlify 或其他支持 Next.js 的平台。确保设置所有必要的环境变量。
（注意，由于我部署到vercel项目报错，我也没法解决，所以我放在netlify）


## 致谢

本项目参考了以下开源项目:

- [aicover](https://github.com/all-in-aigc/aicover) - 提供了AI封面生成的灵感和参考




## 许可证

[MIT License](LICENSE)

## 联系方式

项目维护者：[Yiquan]
邮箱：[yiq.yan@foxmail.com]

```

