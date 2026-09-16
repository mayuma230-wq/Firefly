# 马俊宇的博客

基于开源主题 [Firefly](https://github.com/CuteLeaf/Firefly) 搭建的个人博客，底座取自 [fqzlr/fqzlr-bk](https://github.com/fqzlr/fqzlr-bk)（MIT 许可）。

本站已完成的改造：
- 全站个人信息（站名 / 作者 / 头像 / 联系方式 / 页脚版权）已替换为本人的
- 移除了原作者的云端服务依赖（评论后端、图床上传 API、统计服务、地图 Key、赞助收款方式）
- 保留了原作者的文章与静态资源，作为学习参考

## 技术栈

Astro · Svelte · Tailwind CSS · Swup · Pagefind · Expressive Code

## 本地开发

```bash
pnpm install
pnpm dev
```

## 构建

```bash
pnpm build
```

构建产物输出到 `dist/`。

## 部署

通过 Cloudflare Pages 的 Git 集成部署，生产分支 `master`，
构建命令 `pnpm build`，输出目录 `dist`。

## 待替换的素材

- `public/assets/images/avatar.svg` —— 占位头像，请换成自己的
- `public/assets/images/home-blinds/` —— 首页百叶窗开场图
- `src/assets/images/avatar.webp` —— 关于页头像

## 许可

代码遵循上游 MIT 许可。仓库内的文章正文与图片素材版权归原作者所有。
