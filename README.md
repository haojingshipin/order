# order 潮汕杂货下单系统
纯静态本地订单网页，托管于 GitHub Pages。

## 功能
- 商品浏览、下单、提交订单
- 内置简繁中文搜索
- 后台管理：新增/编辑/删除商品、导出数据
- 数据保存在浏览器本地 localStorage，无需服务器、不用数据库

## 访问地址
https://haojingshipin.github.io/order/

## 后台入口
页面底部「⚙️ 管理入口」，默认密码：`8888`
> 建议上线后自行修改密码

## 部署说明
1. 仓库根目录放置 index.html
2. 根目录添加 `.nojekyll` 文件，关闭 Jekyll
3. GitHub Pages 设置：Deploy from a branch，main 分支、根目录 /

## 注意
- 所有订单、商品数据存在打开网页的这台手机/电脑本地
- 清除浏览器缓存会丢失数据，后台记得定期导出备份
- 适合小商户内部接单使用
