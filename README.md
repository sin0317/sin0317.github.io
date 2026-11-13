# sin · 说明书

一个把自己写成药品说明书的个人主页。

## 为什么是这个形式

药品说明书是少数**被强制要求写缺点**的文件。用这个形式做自我介绍，「诚实」就成了结构的一部分，而不是额外加一段自我批评。

栏目映射：药品名称 / 成份 / 适应症 / 不良反应 / 禁忌 / 批准文号与证据 / 贮藏。

## 技术

- 单文件 `index.html`，零框架、零依赖、零第三方请求
- 纯 CSS 变量控制配色；`prefers-reduced-motion` 已适配
- 有打印样式（说明书本来就该能打印）
- 移动端 390px 已验证无溢出

## 本地预览

双击 `index.html` 即可。

## 线上地址

**https://sin0317.github.io/**

仓库：`sin0317/sin0317.github.io`（main 分支根目录，Pages 自动发布）

## 发布到 GitHub Pages

本项目已部署。改完内容推一次即可：

```bash
cd D:/WorkBuddy/personal-home
git add -A && git commit -m "update"
git push
```

Pages 会在 1 分钟内自动重建。

## 待补

- [ ] 真实联系方式（GitHub / 邮箱 / 微信二维码）
- [ ] 产品链接（4 款产品的线上地址）
- [ ] 是否放照片
- [ ] 是否公开真名与学校
