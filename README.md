# 守护夕阳 — 老人防骗维权资讯站

## 网站已创建内容

### 页面文件
- `index.html` — 首页（完整，包含6大骗术分类、最新文章、热线条线等）
- `article-ai-fraud.html` — 深度文章：AI换脸诈骗（完整，约4000字，含真实案例、识别方法、维权步骤）

### 待创建（后续我会陆续补充）
- `article-healthcare.html` — 保健品诈骗
- `article-telecom.html` — 电信网络诈骗
- `article-investment.html` — 投资理财陷阱
- `article-gift.html` — 中奖/抽奖诈骗
- `article-relative.html` — 假冒亲属诈骗
- `article-social.html` — 养老服务诈骗
- `article-report-guide.html` — 报警维权指南
- `article-elderly-law.html` — 老人法律权益
- `article-common-cases.html` — 案例TOP10
- `article-healthcare-detail.html` — 保健品深度揭秘

---

## 如何免费部署上线

### 方案一：Vercel（推荐，最简单）

**优点：** 免费、自动HTTPS、CDN加速、绑定域名简单

**步骤：**

1. **创建GitHub仓库**
   - 去 github.com 注册/登录
   - 点击右上角 "+" → "New repository"
   - 仓库名填：`laofang-pc`（或其他名字）
   - 选择 Public（Vercel免费版需要Public仓库，或连接GitHub）
   - 点击 "Create repository"

2. **上传网站文件**
   - 进入新仓库，点击 "uploading an existing file"
   - 把 `laofang-pc` 文件夹里的所有文件拖进去
   - 点击 "Commit changes"

3. **连接Vercel部署**
   - 去 vercel.com 注册/登录（用GitHub账号）
   - 点击 "Add New" → "Project"
   - 选择刚才创建的GitHub仓库
   - 其他全部默认，点击 "Deploy"
   - 等待30秒，自动上线！

4. **访问你的网站**
   - Vercel会给你一个免费域名，如：`laofang-pc.vercel.app`
   - 打开即可访问！

5. **绑定自己的域名（可选）**
   - 在Vercel项目设置 → Domains → 添加你的域名
   - 去阿里云/腾讯云买一个域名（如 laofang.cn，约50元/年）
   - 按提示配置DNS即可

---

### 方案二：Netlify（同样免费）

**步骤类似Vercel：**
1. 去 netlify.com 注册
2. 选择 "Add new site" → "Deploy manually"
3. 把 `laofang-pc` 文件夹拖进去
4. 立即上线，获得 `xxx.netlify.app` 链接
5. 可绑定免费子域名或自定义域名

---

### 方案三：GitHub Pages（完全免费，无需注册其他账号）

**步骤：**

1. 在GitHub上创建仓库（同上）
2. 进入仓库 Settings → Pages
3. Source 选择 "Deploy from a branch"
4. Branch 选择 "main"，文件夹选择 "/ (root)"
5. 点击 Save
6. 等1-2分钟，网站在 `https://你的用户名.github.io/仓库名` 上线

---

## 本地预览

双击 `index.html` 即可在浏览器中预览网站效果。

---

## 内容更新频率

我会持续为你更新网站内容，包括：
- 新的骗术类型文章
- 最新诈骗案例警示
- 防骗技巧和维权指南
- 定期SEO优化

---

## 技术说明

- 纯静态网站，无需服务器（零维护成本）
- 响应式设计，适配手机/平板/电脑
- 使用 Google Fonts（中文字体）
- 所有功能纯前端实现，无需后端

---

## 变现计划

**第一阶段（0-3个月）：积累内容**
- 持续更新文章，提升SEO权重
- 申请 Google AdSense（需网站有一定内容后申请）
- 开始获取搜索流量

**第二阶段（3-6个月）：变现起步**
- 接入广告（AdSense + 百度联盟）
- 添加适老化产品推荐（淘客佣金）
- 开始有稳定搜索流量

**第三阶段（6个月+）：规模化**
- 扩大内容覆盖范围
- 推出付费防骗手册/电子书
- 承接品牌广告

---

*此文档由 QClaw AI 助手生成 | 守护夕阳项目*
