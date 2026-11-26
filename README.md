# 瑞盖体育商城管理 Web

负责运营、财务、仓库、销售和客服等后台管理界面，通过后端 API 访问业务数据。小程序属于独立客户端范围。

本仓库已初始化协作规范与基础 CI，尚未创建应用工程或业务实现。

关联仓库：[rigour-mall-backend](https://github.com/ethan-jus/rigour-mall-backend)。

## 技术栈状态

管理 Web 的框架、组件库、Node.js 与包管理器版本尚未在本轮确定。首次工程初始化 PR 应明确稳定兼容版本、提交锁文件，并建立真实的类型检查与生产构建；本轮不擅自选定框架或生成业务页面。

## 开发协作

先阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 和 [AGENTS.md](AGENTS.md)。使用功能分支提交 PR；远端只允许 Squash 合并，合并后自动删除源分支。

当前检查为 `repository-policy`，仅检查仓库规范，不代表应用已编译或业务测试已通过。

**仓库已公开，main 分支保护已启用。** 所有变更必须通过 PR，由另一位有写权限的同事批准，且 GitHub Actions 的 `repository-policy` 检查通过后才能合并；管理员同样受约束。详细规则见 CONTRIBUTING.md。

## 成员邀请

所有者可以在[成员管理入口](https://github.com/ethan-jus/rigour-mall-admin-web/settings/access)选择 Add people，按 GitHub 用户名或邮箱定向邀请；对方接受后获得协作写入权限。公开代码无需邀请即可阅读，该入口不是免邀请获得写权限的链接。

仓库为公开，代码、提交历史及 Actions 日志可被查看。未发布开源许可证，不代表授予任意使用或再分发权利。
