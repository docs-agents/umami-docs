# umami-docs

> 文档已翻译为简体中文。

这是一个使用 [Create Fumadocs](https://github.com/fuma-nama/fumadocs) 生成的 Next.js 应用程序。

## 快速开始

运行开发服务器：

```bash
npm run dev
# 或
pnpm dev
# 或
yarn dev
```

在浏览器中打开 http://localhost:3000 查看结果。

## 项目结构

您可以在项目中看到以下内容：

- `lib/source.ts`：内容源适配器代码，[`loader()`](https://fumadocs.dev/docs/headless/source-api) 提供访问内容的接口。
- `lib/layout.shared.tsx`：布局的共享选项，可选但建议保留。

| 路由                        | 描述                               |
| --------------------------- | ---------------------------------- |
| `app/(home)`                | 落地页和其他页面的路由组。          |
| `app/docs`                  | 文档布局和页面。                    |
| `app/api/search/route.ts`   | 搜索的路由处理器。                  |

### Fumadocs MDX

项目中包含了 `source.config.ts` 配置文件，您可以自定义不同的选项，如 frontmatter schema。

详细说明请阅读 [Introduction](https://fumadocs.dev/docs/mdx)。

## 了解更多

要了解更多关于 Next.js 和 Fumadocs 的信息，请查看以下资源：

- [Next.js 文档](https://nextjs.org/docs) - 了解 Next.js 功能和 API。
- [学习 Next.js](https://nextjs.org/learn) - 交互式 Next.js 教程。
- [Fumadocs](https://fumadocs.dev) - 了解 Fumadocs
