# 社团搭子 AI

高校社团招新智能匹配平台的官网型仓库。

当前仓库包含：

- 首页产品站与交互式匹配 Demo
- GitHub Pages 自动部署配置
- 完整产品文档 [PRD.md](./PRD.md)

## 当前上线能力

当前部署方式是 GitHub Pages，因此适合承载：

- 产品官网
- 动画与前端交互
- 匹配演示与筛选 Demo
- PRD / 文档沉淀

不适合直接承载真实后端能力，例如：

- 登录鉴权
- 数据库存储
- 报名写入
- 通知推送

这些建议在后续通过 API、serverless 或独立后端接入。

## 部署

1. 提交代码到 `main`
2. 打开 GitHub 仓库 `Settings > Pages`
3. 选择 `GitHub Actions`
4. 等待 workflow 完成部署
