# 心电社区桌面版
心电社区桌面版使用了[Nuxt3](https://nuxt.com)作为前端，使用[Tauri](https://tauri.app/zh-cn/)打包成App。

## 部署

首先下载所需要的包

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## 使用Tauri
```bash
# 下载Tauri
cargo install tauri-cli
# 初始化
cargo tauri init
# 启动项目
cargo tauri dev
```