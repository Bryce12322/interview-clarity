# 面试表达检查 · interview-clarity

检查、精简和改写产品经理、AI 产品面试中的项目介绍、问答与逐字稿。

先让面试官听懂产品形态、跟上因果、辨认个人职责，再呈现判断、贡献及产品与 AI 能力。保留真实事实，不编造职责、数据或成果。

## 安装

将本仓库克隆到 Codex 的 skills 目录：

```bash
git clone https://github.com/Bryce12322/interview-clarity.git ~/.codex/skills/interview-clarity
```

如果该目录已经存在，请先备份，避免覆盖本地修改。安装后重新开启会话。

## 使用

在对话中输入，并附上你的文稿：

```text
请用 $interview-clarity 检查我的面试项目介绍，找出第一次听不懂的位置，给出必要的局部改写。
```

也可以要求精简到指定时长、比较两个版本，或把后半段串成连贯口述稿。

## 检查内容

- 产品形态：谁在什么场景，如何操作，得到什么反馈。
- 逻辑与判断：观察如何形成判断，选择如何回应问题。
- 职责与贡献：准确区分本人工作和团队成果。
- 详略分配：首轮讲清主线，追问展开产品规则与 AI 机制。
- 事实边界：区分设计意图、实际交付、验证反馈与业务效果。

默认给出听众复述、最重要的理解障碍与必要的局部改写，不强制评分或全文重写。

## 文件

- [SKILL.md](SKILL.md)：完整执行规则。
- [references/examples.md](references/examples.md)：虚构练习案例，用于说明检查方法。
- [agents/openai.yaml](agents/openai.yaml)：显示名称与默认提示词。
