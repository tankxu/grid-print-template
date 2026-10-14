# 空白网格 · 打印模板

可参数化的英文三线格和方格纸打印工具。纯 HTML、CSS、JavaScript，无外部依赖，配置保存在浏览器本地。

## 使用

直接用浏览器打开 `index.html`，选择模板并调整参数，点击“打印 / 存为 PDF”。

打印时选择相同纸张和方向、100% 缩放、关闭页眉页脚。建议使用打印机的 Fine 或更高质量模式。

- 英文三线格：可配置组数、三线高度、组间空白和虚线。
- 方格纸：可配置行列数、格宽、格高和居中。
- 支持 A4、A5、Letter、横纵向、多页、线宽及颜色。
- 支持配置 JSON 导入和导出。

## Cloudflare Pages

构建命令：`npm run build`

输出目录：`dist`

手动部署：

```sh
npm run build
wrangler pages deploy dist --project-name grid-print-template
```
