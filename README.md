# 👋 支一郎 / Zhiyilang

> RPA 开发 → AI Agent 工程。**把影刀/UiBot 流程编译成可运行的 AI Agent，并审计它们的可靠性。**

我是支一郎，上海的全日制大专（计算机应用技术—大数据方向）出身，1 年 RPA 实战经验，现在把主业从 RPA 转向 LLM / Agent 应用。这个 GitHub 是我从「自动化执行」走向「智能体工程」的公开作品集。

## 🛠️ 零依赖命令行工具（纯 Python 标准库，离线可跑）

下载单个 `.py` 文件即可运行，无需 `pip install`，无网络请求，跨 Win/Mac/Linux。

| 工具 | 用途 | 链接 |
|------|------|------|
| **md2html** | Markdown → 带样式的 HTML，离线、零依赖 | [Zhiyilang/md2html](https://github.com/Zhiyilang/md2html) |
| **csvdiff** | 按主键对比两个 CSV/JSON，报告新增/删除/字段变更 | [Zhiyilang/csvdiff](https://github.com/Zhiyilang/csvdiff) |
| **dupescan** | 用 SHA-256 跨目录查找重复文件 | [Zhiyilang/dupescan](https://github.com/Zhiyilang/dupescan) |
| **lanshare** | 同 Wi-Fi 下手机⇄电脑互传文件（纯 stdlib） | [Zhiyilang/lanshare](https://github.com/Zhiyilang/lanshare) |
| **billfusion** | 合并微信/支付宝 CSV 账单，分类去重出报表 | [Zhiyilang/billfusion](https://github.com/Zhiyilang/billfusion) |

## 🤖 RPA → AI Agent 工具链

| 工具 | 用途 | 技术 |
|------|------|------|
| [**rpa2agent**](https://github.com/Zhiyilang/rpa2agent) | 把 RPA 流程 JSON 编译成可运行 AI Agent 计划（loop/condition 安全求值，可导出独立 .py） | Python · 零依赖 |
| [**rpaaudit**](https://github.com/Zhiyilang/rpaaudit) | RPA 流程静态审计：明文密钥、死循环、脆弱选择器、竞态等 6 类反模式 | Python · 零依赖 |

上述工具均为**纯标准库实现**，自带 README、英文 SEO topics 与 MIT 许可，已公开上线。

## 🏆 竞赛与实战

- 微软 × 英超 **Inside the Game** 开发者黑客松（可解释比赛情报智能体）
- 40+ 条 AI 竞赛管线（Collusion Sprint、AnySearch、QuorumPilot、ARC Prize、迪拜 Create AI Agents 等），代码与提交物料全部公开就绪
- 腾讯 TSRC 漏洞赏金（AI 安全方向合规方法论）

## 💡 我擅长

- RPA 流程设计、逆向与重构（影刀 / UiBot）
- 把确定性自动化升级为带 LLM 决策的 Agent
- Agent 可靠性：静态审计、契约测试、可解释性
- 零依赖、可移植、可审计的命令行工具开发

## ☕ 支持与定制

如果这些工具帮你省了时间，欢迎在 **[爱发电 (afdian)](https://afdian.com/a/Zhiyilang)** 请我喝杯咖啡 ⭐。
企业级定制（私有规则、影刀/UiBot 专属 lint、接入内部 CI/CD）欢迎私信洽谈。

---

<sub>📫 联系方式请见各仓库或爱发电主页。作品集由自动化维护，工具持续更新。</sub>
