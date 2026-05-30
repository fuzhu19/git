# GitHub 小白保姆级入门教程

> 从零到上手完全指南 · 解决中国用户最常遇到的问题  
> 注册耗时约 15 分钟 · 基础操作 1 周可掌握

---

## TL;DR 一分钟速览

| 项目 | 说明 |
|------|------|
| **GitHub 是什么** | 基于 Git 的代码托管平台，可以存储代码、协作开发、展示项目 |
| **价格** | **免费版完全够用**，个人开发者无需付费；学生可申请价值数千美元的免费福利包 |
| **中国能用吗** | 可以直接访问，偶尔不稳定，本文提供多种加速方案 |
| **注册耗时** | 约 10-15 分钟（含邮箱验证和 2FA 设置） |
| **学习周期** | 基础操作 1 周可掌握，熟练使用约 1 个月 |

### Git 核心命令速查表

| 命令 | 说明 |
|------|------|
| `git clone <url>` | 下载远程仓库到本地 |
| `git status` | 查看文件修改情况 |
| `git add .` | 将所有修改加入暂存区 |
| `git commit -m "说明"` | 保存修改到本地仓库 |
| `git push` | 上传到远程仓库 |
| `git pull` | 下载远程最新代码 |

**日常工作流程：** `编辑代码 → git add . → git commit -m "说明" → git pull → git push`

---

## 一、GitHub 是什么？为什么要学？

### What：GitHub 到底是干什么的

**Git** 是一个版本控制工具，帮你记录代码的每一次修改，就像游戏存档一样可以随时回退。**GitHub** 则是基于 Git 的在线平台，让你可以把代码存到云端、和别人协作开发、展示自己的项目作品。

> 💡 **简单类比：** Git 是你电脑上的记账软件，GitHub 是把账本存到云端的银行，还能和朋友共享账本。

### Why：为什么要学 GitHub

1. **求职必备** — 90% 以上的技术岗位都要求掌握 Git/GitHub
2. **作品展示** — GitHub 就是程序员的"作品集"，面试官会看你的 GitHub 主页
3. **学习资源** — 全球最优质的开源项目和代码都在 GitHub 上
4. **免费福利** — 学生可以申请价值数千美元的开发工具包

### 基础信息速览

| 项目 | 内容 |
|------|------|
| 官网 | https://github.com |
| 所属公司 | 微软（2018 年收购） |
| 用户规模 | 全球 1 亿+ 开发者 |
| 中国访问 | ✅ 可直接访问（偶尔不稳定） |
| 中文界面 | ⚠ 部分支持（可在设置中切换简体中文） |
| 免费版 | ✅ 功能完整，个人使用完全够用 |

---

## 二、注册账号：保姆级步骤详解

### 准备工作

- **浏览器**：推荐 Chrome、Firefox 或 Edge（不支持 IE）
- **邮箱**：推荐使用 QQ 邮箱或 Gmail（163 邮箱可能收不到验证码）
- **网络**：如遇页面加载慢，可能需要科学上网

### 注册步骤（约 10 分钟）

**第 1 步：访问注册页面**

打开浏览器，访问 https://github.com/signup ，点击页面上的 **Sign up** 按钮开始注册。

**第 2 步：填写邮箱地址**

在输入框中输入你的邮箱地址，系统验证通过后会显示绿色勾勾 ✓，点击 **Continue** 继续。

**第 3 步：设置密码**

> 🔐 **密码要求：**
> - 至少 8 个字符，且必须包含至少一个小写字母
> - 或者纯数字需要 15 个字符以上
> - 建议设置包含大小写字母、数字的强密码

**第 4 步：选择用户名**

用户名是你在 GitHub 上的唯一标识，选择时请注意：
- 只能用英文字母、数字和连字符 `-`
- 不能以连字符开头或结尾
- 不能使用中文
- 建议使用简洁、专业的名称，如 `zhangsan` 或 `john-doe`

**第 5 步：邮件订阅选择**

系统询问是否接收产品更新邮件，输入 `n` 拒绝或 `y` 接受，点击 **Continue**。

**第 6 步：完成人机验证**

点击开始解谜，按提示完成图像识别任务。如果验证码加载不出来，尝试更换浏览器或使用科学上网。

**第 7 步：邮箱验证**

GitHub 会发送一封包含 6-8 位数字验证码的邮件到你的邮箱。打开邮件，将验证码填入网页，即可完成注册。

### 必须设置：两步验证 (2FA)

> ⚠ **重要提醒：** GitHub 强制要求所有用户启用两步验证，不设置会导致部分功能受限。由于 GitHub 的短信验证**不支持中国 +86 手机号**，你必须使用验证器 App。

**推荐方式：使用验证器 App**

1. 在手机应用商店下载 **Microsoft Authenticator** 或 **Google Authenticator**
2. 登录 GitHub → 点击头像 → Settings → Password and authentication
3. 点击 **Enable two-factor authentication**
4. 用手机 App 扫描页面上的二维码
5. 输入 App 显示的 6 位验证码
6. 下载并保存恢复码（**极其重要！丢失后账号可能无法恢复**）

### 常见注册问题解决

| 问题 | 解决方案 |
|------|----------|
| 邮箱收不到验证码 | 检查垃圾邮件文件夹；避免使用 163 邮箱 |
| 验证码加载失败 | 更换浏览器；清除缓存；使用科学上网 |
| 页面卡住不跳转 | 尝试用手机浏览器完成注册 |
| 2FA 没有中国手机选项 | 必须使用验证器 App，不支持短信验证 |

---

## 三、核心功能实操教程

### 功能 1：创建你的第一个仓库（Repository）

仓库就是存放项目代码的地方，相当于一个项目文件夹。

**创建步骤：**

1. 登录 GitHub，点击页面右上角的 **+** 图标
2. 选择 **New repository**
3. 填写仓库名称（如 `my-first-project`）
4. 选择 **Public**（公开）或 **Private**（私有）
5. 勾选 **Add a README file**（推荐）
6. 点击 **Create repository**

> 🎉 恭喜！完成后你就拥有了第一个 GitHub 仓库！

### 功能 2：Git 基础操作

在使用 Git 命令前，需要先安装 Git：
- Windows 用户访问 https://git-scm.com/download/win 下载安装
- Mac 用户在终端执行 `xcode-select --install`

**首次使用配置：**

```bash
git config --global user.name "你的名字"
git config --global user.email "你的邮箱"
```

**克隆仓库到本地：**

```bash
git clone https://github.com/用户名/仓库名.git
```

**日常工作流程：**

```bash
# 1. 进入项目文件夹
cd 仓库名

# 2. 修改代码后，添加所有改动
git add .

# 3. 提交到本地（-m 后写本次修改说明）
git commit -m "添加了新功能"

# 4. 推送到 GitHub
git push
```

### 功能 3：GitHub Desktop 图形化工具

如果你觉得命令行太难，可以使用 GitHub 官方的图形化工具。

**安装步骤：**

1. 访问 https://desktop.github.com/download/
2. 下载对应系统版本并安装
3. 登录 GitHub 账号

**基本操作：** 左侧显示文件变化 → 底部输入提交信息 → 点击 **Commit to main** → 点击 **Push origin** 推送到远程

### 功能 4：GitHub Pages 免费建站

GitHub Pages 可以让你**免费搭建个人网站**。

**创建步骤：**

1. 创建一个名为 `用户名.github.io` 的仓库
2. 上传一个 `index.html` 文件作为首页
3. 进入仓库 → Settings → Pages → Source 选择 main 分支
4. 几分钟后访问 `https://用户名.github.io` 即可看到你的网站

### 功能 5：Issues 任务管理

Issues 用于记录 Bug、提出建议或管理任务。

**创建 Issue：** 进入仓库 → 点击 **Issues** 标签 → 点击 **New Issue** → 填写标题和详细描述 → 点击 **Submit new issue**

### 功能 6：Pull Request 协作流程

当你想为别人的项目贡献代码时，需要通过 PR（Pull Request）：

1. **Fork**：点击目标仓库右上角的 **Fork** 按钮，复制到自己账号
2. **Clone**：克隆到本地并创建新分支修改代码
3. **Push**：推送修改到自己的 Fork 仓库
4. **Create PR**：回到 GitHub 点击 **Compare & pull request**
5. 等待项目维护者审核和合并

---

## 四、费用详解：Free 够用吗？

### 定价对比表

| 版本 | 价格 | 核心功能 | 适合人群 |
|------|------|----------|----------|
| **Free** | $0 | 无限公/私有仓库、2000 分钟 CI/CD、500MB 存储 | 个人开发者首选 |
| **Pro** | $4/月 | 3000 分钟 CI/CD、2GB 存储、高级代码审查 | 个人高级需求 |
| **Team** | $4/用户/月 | 团队协作功能、多审查者、Web 支持 | 中小团队 |
| **Enterprise** | $21/用户/月起 | SSO 单点登录、高级审计、自托管选项 | 大型企业 |

### 省钱技巧

**🎓 技巧 1：学生免费获取 Pro + Copilot**

如果你是在校学生，强烈推荐申请 **GitHub Student Developer Pack**：

- GitHub Pro 免费
- GitHub Copilot Pro 免费（AI 编程助手，价值 $19/月）
- JetBrains 全套 IDE 免费
- DigitalOcean $200 云服务额度
- 以及 100 多个合作伙伴的免费福利

申请地址：https://education.github.com/pack/join

**💡 技巧 2：年付更划算**

付费计划选择年付通常可节省约 10-17% 的费用。

**💎 技巧 3：Free 版对个人完全够用**

- 无限私有仓库
- 每月 2000 分钟的 GitHub Actions（自动化 CI/CD）
- 120 核心小时的 Codespaces 云开发环境

### 支付方式说明

| 方式 | 状态 |
|------|------|
| Visa/Mastercard 信用卡 | ✅ 推荐使用 |
| PayPal | ✅ 可绑定国内信用卡 |
| 支付宝/微信 | ❌ 不支持 |

---

## 五、真实优缺点分析

### 👍 优点：为什么选择 GitHub

- **社区最大**：1 亿+ 开发者，几乎所有优质开源项目都在这里
- **功能完善**：Issues、Projects、Actions、Pages 等一站式解决
- **免费慷慨**：免费版功能强大，个人使用完全够用
- **求职加分**：GitHub 主页就是程序员的简历，面试官会看
- **AI 加持**：Copilot 是目前最强的 AI 编程助手
- **生态丰富**：与 VS Code、各种 CI/CD 工具深度集成

### 👎 缺点：需要注意的问题

- **中国访问不稳定**：偶尔加载慢或打不开，需要配置加速
- **图片加载问题**：头像和 README 图片经常加载失败
- **没有中文客服**：遇到问题只能看英文文档或社区求助
- **2FA 不支持中国手机**：必须使用验证器 App
- **学习曲线**：Git 概念对新手有一定门槛

---

## 六、竞品对比：GitHub vs GitLab vs Gitee vs Bitbucket

### 功能对比表

| 平台 | 中国访问 | 社区活跃度 | 特色 |
|------|---------|-----------|------|
| **GitHub** | ⚠ 偶尔不稳定 | ⭐⭐⭐⭐⭐ | AI 助手最强 |
| **GitLab** | ⚠ 一般 | ⭐⭐⭐⭐ | DevOps 一体化最强 |
| **Gitee（码云）** | ✅ 极快 | 中文 ✅ | 国内首选 |
| **Bitbucket** | ⚠ 一般 | — | Atlassian 生态深度集成 |

### 如何选择？

| 场景 | 推荐平台 |
|------|----------|
| 学习编程、求职展示 | GitHub（全球标准，面试官认可） |
| 参与开源项目 | GitHub（所有主流开源项目都在这） |
| 需要最快访问速度 | Gitee（国内服务器，速度最快） |
| 公司内部项目、数据合规 | Gitee（符合国内法规） |
| 完整 DevOps 一体化 | GitLab（CI/CD 功能最完善） |
| 已使用 Jira/Confluence | Bitbucket（Atlassian 生态深度集成） |

### 💡 双平台策略推荐

对于中国用户，推荐 **GitHub + Gitee 双平台策略**：

- 主仓库放在 GitHub（利用全球社区和求职价值）
- 用 Gitee 导入 GitHub 仓库作为镜像（加速克隆下载）

---

## 七、常见问题 FAQ

### Q1：Git 和 GitHub 有什么区别？

**Git** 是一个版本控制工具，安装在你的电脑上，用于管理代码版本。**GitHub** 是基于 Git 的云端平台，用于存储代码和协作。简单说：**Git 是工具，GitHub 是平台**。

### Q2：GitHub 在中国能正常访问吗？

可以直接访问，**无需翻墙**。但偶尔会出现加载慢或图片显示不出来的情况。

**解决方案：** 修改 hosts 文件、使用加速工具（如 dev-sidecar），或配置 Git 代理。

### Q3：`git clone` 速度很慢怎么办？

**推荐方案：**

- 使用浅克隆：`git clone --depth=1 <url>`
- 使用 Gitee 导入后从 Gitee 克隆
- 配置 Git 代理：`git config --global http.proxy http://127.0.0.1:7890`

### Q4：为什么 2FA 设置没有中国手机选项？

GitHub 的短信验证**不支持 +86 号码**。你必须使用验证器 App（如 Microsoft Authenticator 或 Google Authenticator）来完成 2FA 设置。

### Q5：提交代码时出现冲突怎么办？

1. 打开有冲突的文件，找到 `<<<<<<< HEAD` 和 `>>>>>>>` 标记
2. 手动选择要保留的代码，删除冲突标记
3. 执行 `git add .` 然后 `git commit -m "解决冲突"`
4. 执行 `git push`

### Q6：如何撤销最后一次 commit？

```bash
# 撤销 commit，保留代码修改
git reset --soft HEAD^

# 完全撤销，代码也回退
git reset --hard HEAD^
```

### Q7：大文件（超过 100MB）怎么上传？

GitHub 限制单文件最大 100MB。解决方案是使用 **Git LFS（Large File Storage）**：

```bash
git lfs install
git lfs track "*.mp4"
git add .gitattributes
git add large_file.mp4
git commit -m "add large file"
git push
```

### Q8：忘记保存 2FA 恢复码怎么办？

如果你还能登录账号，立即到 Settings → Password and authentication → Recovery codes 重新生成并保存。如果已经无法登录且没有恢复码，需要联系 GitHub 支持团队，可能需要提供身份证明。

---

## 八、Checklist 行动清单

### 📅 第一天：完成注册

- [ ] 访问 github.com/signup 注册账号
- [ ] 完成邮箱验证
- [ ] 下载验证器 App 并设置 2FA
- [ ] 保存恢复码到安全位置
- [ ] 完善个人资料（头像、简介）

### 📅 第一周：基础操作

- [ ] 安装 Git（git-scm.com）
- [ ] 配置用户名和邮箱
- [ ] 创建第一个仓库
- [ ] 学会 `git clone/add/commit/push/pull`
- [ ] 尝试安装 GitHub Desktop

### 📅 第二周：进阶功能

- [ ] 配置 SSH Key（免密码操作）
- [ ] 学习分支操作（branch/merge）
- [ ] 创建第一个 Issue
- [ ] 尝试 Fork 一个项目并提交 PR
- [ ] 如遇访问慢，配置加速方案

### 📅 第三周：实战应用

- [ ] 用 GitHub Pages 搭建个人网站
- [ ] 完成一个小项目并推送到 GitHub
- [ ] 如果是学生，申请 Student Developer Pack
- [ ] 尝试 GitHub Actions 自动化

---

## 九、延伸学习资源

### 官方资源

- [GitHub 官方文档（中文）](https://docs.github.com/zh)
- [Git 官方教程](https://git-scm.com/book/zh/v2)
- [GitHub Skills](https://skills.github.com) — 交互式学习

### 中文教程推荐

- [廖雪峰 Git 教程](https://www.liaoxuefeng.com/wiki/896043488029600) — **入门首选**
- [菜鸟教程 Git](https://www.runoob.com/git/git-tutorial.html)
- [Learn Git Branching](https://learngitbranching.js.org/?locale=zh_CN) — 可视化学习

### 练手项目

- [First Contributions](https://github.com/firstcontributions/first-contributions) — 完成你的第一次开源贡献
- 创建个人主页仓库：创建一个与用户名同名的仓库，README 会显示在你的 GitHub 首页

### 工具推荐

| 工具 | 链接 | 用途 |
|------|------|------|
| GitHub Desktop | https://desktop.github.com | 图形化 Git 工具 |
| VS Code | https://code.visualstudio.com | 推荐编辑器，内置 Git 支持 |
| dev-sidecar | https://github.com/docmirror/dev-sidecar | GitHub 访问加速 |
| SwitchHosts | https://github.com/oldj/SwitchHosts | 自动更新 hosts |

---

> 🚀 **最后提醒：** GitHub 的核心价值在于"用起来"。不要追求一次性学会所有功能，先从 `clone → add → commit → push` 这个基本流程开始，在实际项目中边用边学才是最快的进步方式。
>
> 祝你 GitHub 之旅顺利！🎉

---

> 📌 **声明：** 本文所有信息均来自公开网络资源，仅供参考和学习使用。GitHub 产品功能和定价可能随时变化，请以官网为准。

**参考来源：**

1. https://github.com
2. https://docs.github.com/zh
3. https://git-scm.com/book/zh/v2
4. https://education.github.com/pack
5. https://desktop.github.com
6. https://www.liaoxuefeng.com/wiki/896043488029600
7. https://www.runoob.com/git/git-tutorial.html
8. https://learngitbranching.js.org/?locale=zh_CN
9. https://gitee.com
10. https://about.gitlab.com
11. https://bitbucket.org
12. https://github.com/docmirror/dev-sidecar
13. https://github.com/oldj/SwitchHosts
14. https://github.com/firstcontributions/first-contributions
15. https://skills.github.com
