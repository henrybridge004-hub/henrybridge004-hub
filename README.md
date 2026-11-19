# Henry

**HR × AI** —— 把 HR 的重复劳动做成工具，把 HR 的判断写成方法。

<sub>An HR who builds tools: automate the repetitive, codify the judgment.</sub>

在一线做招聘、培训和组织发展。习惯是：做过的活尽量变成别人能直接拿去用的东西，而不是留在自己的电脑里。

**AI 负责重复的部分，人负责判断的部分。**

## `01` 我在做什么

- **招聘**：从简历筛选、批量触达到面试安排、台账复盘，尽量把整条链路上的手工活拿掉。
- **培训**：课程上架、命名、分类这类事交给脚本，人不重复做第三遍。
- **组织发展**：用诊断流程和证据分级，替掉「我觉得」「大家都说」。

## `02` 我能提供什么

<sub>What you can take away from here.</sub>

| 你可能遇到的情况 | 我能帮上的 |
| --- | --- |
| 想在招聘、培训里用上 AI，但不知道从哪一步下手 | 告诉你在真实流程里哪一步先做、哪一步先别碰；工具是现成的，装上去就能试 |
| 手上堆着重复活：筛简历、传课程、对数据 | 先判断哪些值得自动化、哪些自动化反而更麻烦，再给一个能跑起来的做法 |
| 团队数据散在各个系统，各看各的 | 台账结构、漏斗口径、权限怎么分（谁能看明细、谁只能看聚合），这套在正式试点里跑过一轮 |
| 述职写成流水账，OD 诊断停在「我觉得」 | 提问清单和判断标准，照着走能出结论 |
| 想自己做一个类似的工具，不确定坑在哪 | 踩过的：平台风控、接口权限、数据边界、打包给别人用 |

以上都不是概念，是能直接拿走用的东西。

## `03` 工具 · 把重复劳动交出去

<sub>Tools: hand the repetitive work to scripts.</sub>

| 工具 | 解决什么问题 | 怎么做的 |
| --- | --- | --- |
| **[boss-zhipin-hr-greet](https://github.com/henrybridge004-hub/boss-zhipin-hr-greet)** | 一天几十上百份简历，手动筛、手动打招呼 | CDP 连本机浏览器，指纹和登录态都是真的；先拉一批简历做人才摸查，跟你校准画像，确认评判准了才分批打招呼（每批 5 个、间隔 10–15 秒），带 dry-run 和操作日志 |
| **[gaozhao-ledger](https://github.com/henrybridge004-hub/gaozhao-ledger)** | 招聘数据散在各个系统，团队各看各的 | 从薪人薪事按 `jobOwners` 取数，生成固定 26 列个人台账、面试反馈明细和公开漏斗，每日增量同步到钉钉 AI 表格；个人明细互相不可见，漏斗和转化率全组可见 |
| **[kuxueyuan-batch-upload](https://github.com/henrybridge004-hub/kuxueyuan-batch-upload)** | 课程一个个手动上架，改名和分类全靠人 | 递归扫描文件夹 → 按「课程名 + 六位日期」改名 → 按目录自动匹配分类 → 输出 Excel 上传计划，配合浏览器自动化批量发布 |

## `04` 方法 · 把判断写成流程

<sub>Methods: write the judgment down so it can be reused.</sub>

- **[od-coach](https://github.com/henrybridge004-hub/od-coach)** —— 用真实工作问题练组织诊断。走八闸门（现象 → 目标 → 背景 → 利益相关者 → 组织现状 → 证据 → 根因 → 干预），根因证据不到 L3 就不给方案，先出待补证据清单。
- **[performance-review-value-extraction](https://github.com/henrybridge004-hub/performance-review-value-extraction)** —— 述职不是流水账。用 Why-How-Result-Capability 四个问题串一条主线：一个项目只讲一件事，能力靠项目证明，不靠自我评价。
- **[vibe-coding-playbook](https://github.com/henrybridge004-hub/vibe-coding-playbook)** —— 把技术名词翻译成「什么时候用、怎么用、能迁移到哪」：60 个能力、180 个迁移场景、182 个术语。单文件 HTML，[在线打开](https://henrybridge004-hub.github.io/vibe-coding-playbook/)。

## `05` 交流

<sub>What we can talk about — say hi any time.</sub>

欢迎随时来聊，比较想聊这几件事：

- **AI 怎么进招聘的真实流程**：从哪一步开始、怎么跟团队交代、卡住的时候怎么退回去
- **工具从「我自己能用」到「同事也能用」**：中间差的权限、配置、出错兜底
- **HR 数据的边界**：哪些能公开、哪些只能内部看、哪些一律不落盘
- **组织诊断和述职**：怎么把「做了什么」讲成「证明了什么能力」

邮箱：henrybridge@qq.com

也可以直接在下面这些仓库里提 Issue，我都会看。

---

<sub>最近更新 2026-11</sub>
