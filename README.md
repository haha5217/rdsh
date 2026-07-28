# 乾安县发展党员时间合理性审核工具

## Cloudflare Pages Git部署设置

- 框架预设：None
- 构建命令：留空；如果界面必须填写，使用`exit 0`
- 构建输出目录：`public`
- 根目录：留空
- 环境变量：不需要

## 文件说明

- `public/index.html`：新版网页，单文件源码，可直接维护。
- `public/_headers`：Cloudflare Pages响应头设置。
- `public/_redirects`：单页访问回退规则。
- `original/rdsh-original-index.html`：从原网站恢复的旧版完整源码，仅供留档，不参与部署。

网站数据仅保存在当前浏览器本地存储中，不上传身份证号等录入数据。
