# 猜猜我是谁

Cloudflare Workers 双人联机游戏项目。

## 部署
1. 将本目录中的所有文件直接上传到 GitHub 仓库根目录（不要再套一层文件夹）。
2. Cloudflare Workers Builds 使用部署命令：`npx wrangler deploy`
3. 不要上传 `node_modules`。

所有游戏网页和成员照片均位于仓库根目录；`.assetsignore` 会阻止 Worker 配置、源码和依赖目录被当作网页资源上传。
