# 白皮书页面维护

访问地址：https://atce-alliance.github.io/white-paper/

本目录为静态网页，不需要安装依赖或运行构建。GitHub Pages 已配置从 `main` 分支根目录发布；将本目录提交到该分支后会自动部署。

## 文件

- `index.html`：白皮书介绍、阅读和下载入口、章节目录与编写团队。
- `style.css`：页面样式与手机适配。
- `assets/ai-short-drama-copyright-v11.pdf`：原始 PDF，未修改。
- `assets/cover.png`：原始 PDF 第 1 页的图片。

## 更新白皮书

1. 上传新 PDF 到 `assets/`，建议使用英文文件名。
2. 在 `index.html` 更新全部 PDF 链接、版本、日期、页数、文件大小、章节标题与对应页码。
3. 如封面变化，重新从新 PDF 第 1 页生成 `assets/cover.png`。
4. 提交后等待 Pages 部署完成，检查手机和电脑上的阅读、下载及章节链接。

浏览器自行提供 PDF 阅读器。`#page=N` 在部分手机或微信浏览器中可能不生效，页面已提供对应说明。

本次仅添加 `/white-paper/` 子页面，联盟根路径首页未另行开发。
