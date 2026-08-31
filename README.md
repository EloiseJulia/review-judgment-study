# 评论判断研究 / Review Judgment Study

一项关于人们如何在 AI 建议下做判断的学术研究。
An academic study on how people make judgments when an AI assistant offers a recommendation.

本研究已经**长安大学伦理审查委员会**审查并批准（批准号 **20260831**）。
Approved by the Ethics Committee of **Chang'an University** (approval no. **20260831**).

---

# 中文说明

## 立即开始

**👉 [点击这里开始实验](https://EloiseJulia.github.io/review-judgment-study/)**

不需要下载，不需要注册，不需要 clone 这个仓库。点开链接直接做就行。

## 你需要知道的

| | |
|---|---|
| **时长** | 约 20 分钟 |
| **设备** | 请用**电脑**（Chrome 或 Edge 最佳）。手机也能打开，但阅读体验差很多 |
| **报酬** | 无。这是无偿自愿参与 |
| **个人信息** | 不收集。没有姓名、没有邮箱、没有学号、没有 IP |
| **数据去向** | **不上传到任何服务器**。只会保存到你自己的电脑上 |

## 你要做什么

1. 点开上面的链接
2. 选择界面语言（中文 / English）——注意**评论原文是英文**，这是研究设计的一部分
3. 阅读知情同意，同意后开始
4. 回答 6 个关于你自己的小问题
5. 阅读 15 条商品评论。每条：
   - 先自己判断这条评论是**正面**还是**负面**，并为把握程度打分
   - 然后会看到一个 **AI 助手的建议**
   - 你可以保持或修改答案，再打一次分
6. 结束后会有一个简短说明

**请给出你自己的真实判断。** 这个任务没有陷阱题，但也不是每道题都有显然的答案——拿不准是正常的。

## ⚠️ 最后一步（很重要）

做完后，页面会**自动把一个 `.csv` 文件下载到你的电脑**，一般在「下载」文件夹里。最后一屏会显示这个文件的具体名字，类似：

```
review_study_beer_a1b2c3d4e5_2026-09-15.csv
```

**请把这个文件发回给邀请你参加的人。**

因为数据不经过任何服务器，这个文件是你作答的**唯一副本**。不发回来，你的参与就无法被计入，前面 20 分钟也就白花了。

> 如果浏览器拦截了下载：最后一屏有「重新下载文件」按钮，还有「以文本方式显示数据」——可以把文本全选复制发给我们，效果一样。

## 一个请求 🙏

**请不要去看这个仓库里的源代码。**

研究要成立，前提是每位参与者面对任务时的信息是一样的。提前研究程序内部会让你的数据无法使用——不会有人指责你，但那份数据只能作废。二十分钟的时间，我们希望它是有价值的。

## 隐私

- 不收集姓名、邮箱、学号、IP 地址、设备信息
- 记录的日期**只精确到天**，不含具体时刻
- 每次参与生成一个随机编号（如 `a1b2c3d4e5`），与你本人无关联
- 数据仅用于本研究，分析完成后销毁
- 参与完全自愿，可随时关闭页面退出；即使做完了，最后一屏也有**「撤回我的数据」**按钮——点了之后导出的文件不含任何作答内容

---

# English

## Start here

**👉 [Click here to begin](https://EloiseJulia.github.io/review-judgment-study/)**

No download, no sign-up, no need to clone this repository.

## What to expect

| | |
|---|---|
| **Time** | About 20 minutes |
| **Device** | Please use a **computer** (Chrome or Edge). It opens on a phone but reads poorly |
| **Payment** | None — this is unpaid, voluntary participation |
| **Personal data** | None collected: no name, email, ID number or IP address |
| **Where data go** | **Nowhere.** Nothing is uploaded; the file is saved on your own computer |

## What you'll do

1. Open the link above
2. Choose an interface language. The **reviews themselves are in English** by design
3. Read the consent screen
4. Answer 6 short questions about yourself
5. Read 15 product reviews. For each one:
   - decide whether it is **Positive** or **Negative**, and rate your confidence
   - then see a recommendation from an **AI assistant**
   - keep or change your answer, and rate your confidence again
6. Read a short closing explanation

**Please give your own honest judgment each time.** There are no trick questions, but not every review is
obvious — feeling unsure is normal.

## ⚠️ The last step (important)

When you finish, a `.csv` file is **downloaded automatically** to your computer, usually into
**Downloads**. The final screen shows its exact name, something like:

```
review_study_beer_a1b2c3d4e5_2026-09-15.csv
```

**Please send that file back to the person who invited you.**

Because nothing passes through a server, that file is the **only copy** of your answers. Without it your
participation cannot be counted and the twenty minutes are wasted.

> If your browser blocked the download, the final screen has a **Download the file again** button and a
> **show the data as text** option — copying that text and sending it works just as well.

## One request 🙏

**Please don't read the source code in this repository.**

The study only works if everyone meets the task with the same information. Studying the code beforehand
makes your data unusable — nobody would blame you, but it would have to be discarded, and we would rather
your twenty minutes counted.

## Privacy

- No name, email, ID number, IP address or device information is collected
- Dates are recorded to the **day only**, never to the hour or minute
- Each session gets a random code (e.g. `a1b2c3d4e5`) unconnected to you
- Data are used for this research only and destroyed after analysis
- Participation is voluntary: close the tab at any time. Even after finishing, the final screen offers
  **Withdraw my data**, which exports a file containing none of your answers

---

## For researchers

This repository contains only the participant-facing instrument: `index.html`, the encoded stimulus
bundle, and a vendored copy of [jsPsych](https://www.jspsych.org/) 7.3.4 under `lib/`. There are no
external requests at runtime, so it also runs offline from a local folder.

The study protocol, power analysis, codebook and analysis scripts are held separately and are not
published here while data collection is open.

Questions about the research should go to the Ethics Committee of Chang'an University, quoting approval
number 20260831.
