# 织序订单跟踪原型 v1.0.0

已于2026年10月19日确认的交互原型。

- [打开在线原型](https://lin-sein.github.io/zhixu-order-prototype/)
- [v1.0.0 发布与静态文件下载](https://github.com/lin-sein/zhixu-order-prototype/releases/tag/v1.0.0)
- [版本说明](CHANGELOG.md)

此仓库保存 GitHub Pages 发布文件，页面位于 `docs/`。源码与测试另存于私有仓库，`release.json` 记录对应源码提交，`docs/version.json` 用于核对线上版本。

页面展示原型示例数据，业务修改保存在访问者自己的浏览器中，附件保存在 IndexedDB。演示账号 `linxiao`，密码 `demo123`；登录、权限和备份用于演示。

更新方式：从对应源码版本执行 `npm run build -- --base=/zhixu-order-prototype/`，将产物同步到 `docs/` 后推送 `main`。GitHub Pages 从 `main` 分支的 `/docs` 发布。版本标签与 Release 保留各次发布记录。
