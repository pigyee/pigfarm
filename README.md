# Leo - Astro Theme With Tailwindcss & MDX


个人网站，使用 [Tailwind](https://tailwindcss.com/), [React.js](https://react.dev/) 和 [Three.js](https://threejs.org/) 构建
文章目录结构（使用MDX格式化文本）
```
...
├── blog
│   ├── en
│   │   ├── some-en-post.mdx
│   │   ├── some-en-post-1.mdx
│   │   └── ...
│   └── zh
│       ├── some-zh-post.mdx
│       ├── some-zh-post-1.mdx
│       └── ...
...
```


### 主题配置

修改 `src/config.ts` 配置文件

- `SITE_FAVICON`: favicon 
- `SITE_LOGO`: logo
- `SITE_TITLE`: 标题
- `SITE_DESCRIPTION`: 描述
- `ME_AVATAR`: avatar
- `LANGUAGES`: 语言
- `MENUS`: 顶部菜单
- `FOOTER_CONTENT`: 页脚


- @astrojs/mdx: <https://docs.astro.build/en/guides/markdown-content/>
- @astrojs/rss: <https://docs.astro.build/en/guides/rss/>
- @astrojs/sitemap: <https://docs.astro.build/en/guides/integrations-guide/sitemap/>
- @astrojs/tailwind: <https://docs.astro.build/en/guides/integrations-guide/tailwind/>
- rough-notation: <https://roughnotation.com/>

### 许可证

- [MIT](LICENSE)
