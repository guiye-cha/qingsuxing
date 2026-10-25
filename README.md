# 焦虑自助干预 · GitHub Pages 部署包

包内文件
- index.html      主页面（打开即是产品页面）
- design-doc.pdf  产品设计方案文档
- .nojekyll       关闭 Jekyll 处理，保证文件原样发布（勿删）

部署（网页上传，不用装 Git）
1 登录 github.com → 右上角 + → New repository
2 Repository name 填一个名字（例如 anxiety-self-help），Visibility 选 Public，点 Create repository
3 在仓库页面点 "uploading an existing file"（或 Add file → Upload files）
4 把本包里全部文件（含 .nojekyll）拖进上传区 → Commit changes
5 左侧 Settings → 左栏 Pages → Build and deployment → Source 选 Deploy from a branch
6 Branch 选 main、文件夹选 /(root) → Save
7 等 1-3 分钟，刷新后页面顶部会显示 https://你的用户名.github.io/仓库名/

更新页面：仓库页 Add file → Upload files → 覆盖 index.html → Commit，约 1 分钟后生效。
