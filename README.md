<!-- 0xfaheng-brand:start -->
**0xfaheng · skillmanager**

[品牌主页与全部公开项目](https://github.com/lairulan) · [当前仓库](https://github.com/lairulan/skillmanager)

> 本仓库是 0xfaheng 使用或维护的 Fork。原项目来源：[Backtthefuture/skillmanager](https://github.com/Backtthefuture/skillmanager)。原作者署名和许可证保留，使用须遵循原项目许可。

微信：`faheng2009` · [X @0xfaheng](https://x.com/0xfaheng) · [YouTube @0xfaheng](https://www.youtube.com/@0xfaheng) · [微信二维码](https://github.com/lairulan#联系与关注)

<!-- 0xfaheng-brand:end -->

---

# Claude Skill Hub

一键扫描并管理所有 Claude Agent Skills 的可视化 Web 管理器。

## 快速开始（一行命令）

```bash
npx github:Backtthefuture/skillmanager
```

首次运行会自动：
1. 下载代码到临时目录
2. 安装依赖
3. 构建前端与服务端
4. 启动服务并打开浏览器到 `http://localhost:3456`

要求：Node.js ≥ 20。

## 本地开发

```bash
git clone https://github.com/Backtthefuture/skillmanager.git
cd skillmanager
npm install
npm run dev       # 启动开发环境（前端 5173 + 后端 3456）
```

生产模式：

```bash
npm run build
npm start
```

## 可选环境变量

- `PORT` — 自定义端口（默认 3456）
- `SKILL_HUB_NO_OPEN=1` — 启动时不自动打开浏览器

## 目录结构

- `server/` — Fastify 后端（API + WebSocket + 文件监听）
- `web/` — React + Vite + Tailwind 前端
- `bin/` — CLI 入口与 prepare 脚本
