# 王静 Jennie · 财务BP作品集 - 部署指引

## 文件结构

```
bp-portfolio/
├── index.html              # 作品集首页
├── taotian.html            # 淘天 case 详情页
├── downloads/              # 可下载文件
│   ├── 淘天BP分析报告.docx
│   └── 淘天BP分析过程_工作簿.xlsx
└── README.md               # 这份说明
```

## 30 秒部署到 GitHub Pages

### 第一步：创建 GitHub 仓库
1. 登录 https://github.com
2. 点击右上角 `+` → `New repository`
3. 仓库名填 `bp-portfolio`（或任意名字）
4. 选 `Public`，勾选 `Add a README file`
5. 点击 `Create repository`

### 第二步：上传文件
**最简单的方式**：网页上传
1. 进入仓库主页，点击 `Add file` → `Upload files`
2. 把 `bp-portfolio` 目录里所有文件直接拖进去（包括 `downloads` 文件夹）
3. 滑到底部，点击 `Commit changes`

### 第三步：开启 Pages
1. 仓库页面点 `Settings` → 左栏 `Pages`
2. `Source` 选 `Deploy from a branch`
3. `Branch` 选 `main`，`/(root)`，点 `Save`
4. 等 1-2 分钟，刷新页面就会看到 `Your site is live at https://你的用户名.github.io/bp-portfolio/`

### 第四步：拿到链接
最终链接：`https://你的用户名.github.io/bp-portfolio/`
淘天 case 直链：`https://你的用户名.github.io/bp-portfolio/taotian.html`

## 简历上怎么放

推荐写法：

```
➢淘天集团FY25财务BP分析（个人独立Case，2026.05）：搭建Driver Tree三层CMR
拆解、UE三视角模型、+75亿CMR增长P&L Bridge归因、FY26五情景敏感性分析
与PDD/JD零售对标，输出12项核心监控KPI及量化BP行动建议；
完整报告 → https://你的用户名.github.io/bp-portfolio/taotian.html
```

把链接做成 Word 超链接（Ctrl+K），右下角放一个 2cm 二维码（用任意二维码生成器扫这个链接生成）。

## 后续维护

### 加 Case 2（滚动预测）
1. 复制 `taotian.html` → 改名 `forecast.html`
2. 修改其中的内容
3. 把 `index.html` 里的 "Case 02 进行中" 区块改成正式发布
4. 重新上传

### 改个人信息
- 邮箱、电话、GitHub：`index.html` 的 `#contact` 区块
- 自我介绍：`index.html` 的 `#about` 区块

### 自定义域名（可选）
如果你买了域名（如 `jennie-bp.com`），在 GitHub 仓库 Settings → Pages → Custom domain 填进去即可。

## 本地预览

直接双击 `index.html` 用浏览器打开就能看到效果。所有样式都内联，无需安装任何工具。
