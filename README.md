# Claude Code购买教程：怎么买？选哪个套餐？多少钱一个月？国内用户如何订阅开通？（附 Pro、Max、Team 全套餐价格对比和 1 美元立减优惠码）

想用上 Claude Code，第一件事不是找下载按钮，而是搞清楚它的收费方式。这个 AI 编程助手能读懂整个代码库、跨文件写功能、修 bug、跑测试、直接提交 commit，但它不单独出售——官方文档写得很明白，大多数使用场景都需要一份 Claude 订阅或 Anthropic Console 账户。

所以“购买 Claude Code”实质上是买一份能使用它的订阅。要回答的问题就三个：选哪个套餐、怎么付款、买完怎么开通。下面按这个顺序讲清楚，价格全部是目前官方公示的数字。

## 购买前先弄明白：Claude Code 能在哪里用

Claude Code 不是一个孤立的命令行工具。它跑在好几个界面上：终端 CLI、VS Code 和 JetBrains 的 IDE 插件（包括 Cursor、Windsurf 这类 VS Code 分支）、独立的桌面应用，以及网页版。这些界面背后是同一套引擎，你在项目里写的 CLAUDE.md 配置、MCP 服务器设置，换一个界面依然生效。

同一份订阅，可以在终端里敲命令，也可以在桌面应用里点按钮看 diff，还能在手机上接着处理没跑完的任务。购买时选的其实不是“某个版本的 Claude Code”，而是用量额度和付款方式。

## Claude Code 全套餐价格对比

官方目前公示的方案一共六种，全部列在这里：

| 套餐 | 价格 | 计费方式 | 核心配置与适用场景 | 购买入口 |
| --- | --- | --- | --- | --- |
| Pro | $17/月（年付 $200 一次付清）或 $20/月 | 月付 / 年付 | 含 Claude Code，可用 Sonnet 4.6 和 Opus 4.7；适合小代码库的短期编程任务 | [ 开通 Pro](https://bewild.ai/?code=ACCPAY) |
| Max 5x | $100/月 | 月付 | 更高用量额度，官方定位是“更大代码库日常使用的划算选择” | [ 开通 Max 5x](https://bewild.ai/?code=ACCPAY) |
| Max 20x | $200/月 | 月付 | 更高用量额度，面向用量最大、模型访问最多的重度用户 | [ 开通 Max 20x](https://bewild.ai/?code=ACCPAY) |
| Team | $20/席/月 | 按席位月付 | 面向 5–150 人团队；自助席位管理，超额按标准 API 费率结算；含 Sonnet 4.6 和 Opus 4.7 | [ 开通 Team](https://bewild.ai/?code=ACCPAY) |
| Enterprise | 需联系销售 | 定制 | Team 全部功能，外加高级安全、数据和用户管理 | [ 咨询 Enterprise](https://bewild.ai/?code=ACCPAY) |
| Claude API | 按量付费 | 按用量结算 | 标准 API 计价，开发者数量不限，无按席位费用 | [ 查看 API 开通](https://bewild.ai/?code=ACCPAY) |

> 两个细节要注意：官方价格页明确标注“展示价格不含适用税费”，并且所有套餐都有用量限制，价格和套餐内容可能调整。付款前以结账页面显示的金额为准。

如果已经有倾向，可以从 [👉 开通入口](https://bewild.ai/?code=ACCPAY) 直接进去，当前优惠码 ACCPAY 可立减 1 美元。还没想好的话，往下看逐个分析。

## 个人用户：Pro、Max 5x 和 Max 20x 怎么选

### Pro：门槛最低的一档

Pro 的官方定位是“在小代码库里做短期编程冲刺”，明确包含 Sonnet 4.6 和 Opus 4.7 两个模型。计费分两种：月付 **$20**；年付一次付清 $200，折合每月 **$17**，一年比月付省 $40。

对刚接触 Claude Code 的人来说，Pro 足够看清它能干什么——补测试、修 lint 错误、解决 merge conflict、升级依赖、写提交信息这些日常活，它都能接手。判断要不要升级很简单：在 Pro 上经常撞用量上限，才需要往 Max 看。

### Max 5x 和 Max 20x：为用量准备的档位

Max 5x 每月 **$100**，官方描述是“在更大代码库里日常使用的划算选择”；Max 20x 每月 **$200**，给“用量最大、模型访问最多”的用户。从命名就能看出来，5x 和 20x 指的是相对 Pro 的用量倍数。

偶尔超几次额度，通常没必要直接跳到 $100 的档位；每天高频使用、代码库规模大，升级才划算。两档之间差 $100，按自己的实际负载选就行。

## 团队和企业：Team 与 Enterprise

Team 每席每月 **$20**，面向 5 到 150 人的团队。几个设计值得注意：席位由管理员自助增减；套餐外的用量按标准 API 费率结算，不用整队强制升档；模型上同样包含 Sonnet 4.6 和 Opus 4.7。

Enterprise 在 Team 的全部能力之上，增加了高级安全、数据和用户管理，价格不公开，需要联系销售。有合规、审计或集中管控需求的组织走这条线。

## 另一条路线：Claude API 按量付费

不想被固定月费绑住，API 是官方给出的替代方案：按标准 API 价格按量结算，开发者数量不限，也不收按席位费用。适合两类情况——用量波动大，或者主要把 Claude Code 接进 CI/CD 跑自动化（比如自动代码审查、issue 分类、日志分析）。

用 Console 账户首次登录 Claude Code 时，系统会自动创建一个 Claude Code 工作区，成本可以集中追踪，这对需要向公司报账的人挺实用。

另外，终端 CLI 和 VS Code、JetBrains 插件还支持接入第三方云渠道：Amazon Bedrock、Google Cloud 的 Agent Platform、Microsoft Foundry。公司如果已经在这几家云上有预算，直接走云渠道计费即可，不用单独开订阅。

## Claude Code 购买和开通的完整流程

**第 1 步：选套餐并完成订阅。** 个人从 Pro 起步，团队看 Team，自动化场景考虑 API。官方订阅以美元计价，在官网完成付款后账号即具备使用资格。

**第 2 步：安装工具。** 最常用的终端 CLI 安装命令如下：

bash
# macOS / Linux / WSL
curl -fsSL https://claude.ai/install.sh | bash

# Windows PowerShell
irm https://claude.ai/install.ps1 | iex

# Windows CMD
curl -fsSL https://claude.ai/install.cmd -o install.cmd && install.cmd && del install.cmd


macOS 也可以用 `brew install --cask claude-code`（稳定版约晚一周，另有 `claude-code@latest` 追最新版）；Debian、Fedora、RHEL、Alpine 有 apt/dnf/apk 包。原生安装会自动后台更新，Homebrew 装的需要手动 `brew upgrade`。

原生 Windows 环境建议先装 Git for Windows，这样 Claude Code 能调用 Bash 工具，没装的话它会退回用 PowerShell；WSL 环境不需要这一步。

不想碰命令行的话，直接装桌面应用：macOS 有 Intel 和 Apple Silicon 通用版，Windows x64 和 ARM64 有各自安装包，Ubuntu/Debian 可以用 apt 安装（beta）。装好后登录，点顶部的 Code 标签就能用——注意这个标签需要付费订阅，没订阅会提示升级。桌面应用内置了 Claude Code，不用再装 CLI。

**第 3 步：登录并验证。** 进入项目目录运行 `claude`，首次使用会引导浏览器完成认证。支持的账户类型：Claude 订阅（Pro/Max/Team/Enterprise，官方推荐）、Claude Console（预付点数）、Amazon Bedrock / Google Cloud Agent Platform / Microsoft Foundry，以及企业自建网关（SSO 登录）。如果设置了 `ANTHROPIC_API_KEY` 并在提示时确认使用，可以跳过登录。

最后跑一下 `claude --version`，能打印版本号就是装好了。会话里输入 `/help` 查看命令，`/resume` 继续上次对话，`/login` 随时切换账号。

## 国内购买 Claude Code：支付环节怎么办

官方订阅按美元计价，国内银行卡直接付款经常走不通，这也是很多人搜“国内怎么买 Claude Code”的原因。常见的解决思路有两条。

第一条是第三方开通渠道。以 bewild.ai 为例，目前挂着 1 美元立减的优惠码 ACCPAY，通过专属链接进入时折扣自动带上，不用手动输码：

[👉 前往 bewild.ai 开通，立减优惠 ACCPAY 已自动生效](https://bewild.ai/?code=ACCPAY)

走第三方渠道之前建议先确认两件事：它支持哪些套餐、接受哪些付款方式。确认和自己的情况对得上再下单，能省掉不少来回。

第二条面向企业用户：如果团队已经在用 Amazon Bedrock、Google Cloud 或 Microsoft Foundry，Claude Code 可以直接接这些云渠道计费，付款走云账户，整个流程对国内企业反而更顺。

## 付费之后，先把这些功能用起来

订阅生效只是开始，Claude Code 真正值回票价的是下面这些能力：

- **CLAUDE.md 项目记忆**：在项目根目录放一个 markdown 文件，每次会话开始时它都会被读取，用来固定代码规范、架构决定和常用库。仓库里已有 AGENTS.md 的话也能直接识别，不用重写。它还会在干活过程中自动积累记忆，跨会话生效。
- **Skills 和 Hooks**：Skills 把可复用的工作流打包成命令，比如 `/review-pr`、`/deploy-staging`；Hooks 能在操作前后自动执行 shell 命令，比如每次改完文件自动格式化、提交前跑 lint。
- **并行任务**：多个会话可以同时开，各占一个 Git worktree；复杂任务还能拆给子代理并行处理，由主代理协调合并结果。
- **定时任务**：Routines 跑在云端，电脑关机也继续执行，还能由 API 调用或 GitHub 事件触发；桌面计划任务在本机跑，直接访问本地文件；CLI 里的 `/loop` 适合会话内快速轮询。
- **跨设备接力**：离开工位后用手机通过 Remote Control 继续本地会话；终端里的长任务可以用 `claude --teleport` 拉回本地继续跑（需要 claude.ai 订阅）。
- **自动化审查**：在 GitHub Actions 或 GitLab CI 里接上 Claude Code，每个 PR 自动做代码审查和 issue 分类；Slack 里 @Claude 报一个 bug，能直接收回一个 PR。

桌面应用的用户还可以按需切换权限模式：Auto 模式由后台分类器拦截高风险操作，Manual 模式每步都要确认，Accept edits 自动接受文件修改，Plan 模式只出方案不动文件——大重构之前先用 Plan 模式看思路，是个稳妥的习惯。

## Claude Code 购买常见问题

**Claude Code 能单独购买吗？**
不能。它跟着 Claude 订阅走（Pro/Max/Team/Enterprise），或者用 Console API 账户、第三方云渠道按量计费。

**价格是最终价吗？**
官方标注展示价格不含适用税费，价格和套餐内容可能调整，结账时以实际显示金额为准。

**Pro 和 Max 的差别在哪？**
核心是用量额度。Pro 定位小代码库的短期任务，Max 5x 和 Max 20x 面向更大代码库的日常和重度使用。还没在 Pro 上遇到过用量限制，就先不用考虑升级。

**买 API 还是买订阅划算？**
看用量形态。固定每天写码，订阅更划算；用量集中、主要跑自动化，API 按量计费更灵活，而且不限开发者数量、不收席位费。

**没有国际信用卡怎么开通？**
可以走第三方开通渠道，比如 bewild.ai，当前有 ACCPAY 立减 1 美元的优惠：[👉 带优惠码进入开通页](https://bewild.ai/?code=ACCPAY)。下单前先确认支持的套餐和付款方式。企业用户也可以直接走 Bedrock 等云渠道。

**怎么确认安装成功？**
新开一个终端窗口运行 `claude --version`，能打印出版本号加 "(Claude Code)" 字样就没问题。
