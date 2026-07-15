# Moday 上架支持页（静态单页）

一个文件搞定三件事：App 介绍 + 支持 FAQ + 隐私政策。中英双语。

## 用法

### 方式 1：GitHub Pages（推荐）

1. 在 GitHub 新建一个公开仓库，例如 `daily-mode-site`
2. 把 `index.html` 提交到 `main` 分支根目录
3. Settings → Pages → Source: `main` / `(root)` → Save
4. 拿到 URL：`https://<你的用户名>.github.io/daily-mode-site/`
5. 在 App Store Connect 填：
   - **支持 URL**：`https://<user>.github.io/daily-mode-site/#support`
   - **隐私政策 URL**：`https://<user>.github.io/daily-mode-site/#privacy`

### 方式 2：Vercel / Cloudflare Pages

把这个文件夹拖进去，一样能发。域名更短更好看：
- `daily-mode.pages.dev`
- `daily-mode.vercel.app`

### 方式 3：自定义域名

如果以后买了 `dailymode.app`，把仓库绑过去就行。

## 改什么

- 邮箱：搜 `nlaiking2026@gmail.com` 替换
- 最后更新日期：搜 `2026-04-22` 替换
- 主题色：CSS 顶部 `--coral`

## 本地预览

```bash
cd submission/website
open index.html
```

或起个服务器：

```bash
python3 -m http.server 8000
# 访问 http://localhost:8000
```
