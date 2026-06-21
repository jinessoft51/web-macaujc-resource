# web-macaujc-resource

## 项目简介

本仓库用于归档和发布多个独立 HTML 页面。这些页面以静态资源的形式存储，不针对任何特定域名或具体网站。仓库本身维护一个通用的页面集合，便于统一管理和访问。

## 目录结构

```
web-macaujc-resource/
├── pages/          # 存放独立 HTML 页面文件
├── assets/         # 页面引用的公共资源（如 CSS、JS、图片等）
├── README.md       # 本文件
└── LICENSE         # 开源许可证
```

- **pages/**：每个 HTML 文件为一个独立页面，文件名即页面标识。
- **assets/**：页面所需的静态资源，按类型或功能子目录组织。

## 页面归档说明

- 所有页面均为纯前端 HTML 文件，不依赖后端服务。
- 页面内容不针对任何具体网站或域名，仅作为独立的资源归档。
- 页面可通过直接打开文件或在 Web 服务器下访问，推荐使用 HTTP 服务以避免跨域问题。

## 维护说明

- 新增页面：在 `pages/` 目录下创建新的 HTML 文件，并在 `assets/` 中添加所需资源。
- 修改页面：直接编辑对应 HTML 文件，注意保持与其他页面的兼容性。
- 删除页面：移除文件及关联资源，确保无残留引用。
- 提交时请附带简要说明，描述变更内容。

## 使用方式

1. 克隆本仓库到本地：
   ```bash
   git clone https://github.com/your-username/web-macaujc-resource.git
   ```
2. 直接在浏览器中打开 `pages/` 下的任意 HTML 文件，或使用本地 Web 服务器（如 `python -m http.server`）进行访问。

## 许可证

本项目采用 [MIT 许可证](LICENSE)。
