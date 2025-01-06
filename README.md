# Nuxt 3 Starter Template

这是一个基于Nuxt 3的快速启动模板，包含以下功能：

- ⚡️ Nuxt 3
- 🎨 UnoCSS
- 🛠 TypeScript
- ✅ ESLint

## 快速开始

1. 克隆仓库

```bash
git clone https://github.com/your-repo/nuxt-starter-template.git
```

2. 安装依赖

```bash
pnpm install
```

3. 启动开发服务器

```bash
pnpm dev
```

## 项目结构

```
.
├── components/       # Vue组件
├── composables/      # 组合式API
├── layouts/          # 布局文件
├── pages/            # 页面路由
├── public/           # 静态资源
└── server/           # API路由
```

## 开发指南

- 添加新页面：在`pages`目录下创建`.vue`文件
- 添加组件：在`components`目录下创建`.vue`文件
- 添加API：在`server/api`目录下创建`.ts`文件

## 部署

### 静态站点生成

```bash
pnpm generate
```

### Node.js服务器

```bash
pnpm build
pnpm start
```

## 许可证

MIT
