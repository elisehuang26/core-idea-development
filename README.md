# Core Idea 创意推导

一个面向品牌策划、创意策略和 agency 提案的中文 Agent Skill。

把消费者观察与产品依据逐步推导成 Core Idea，解释创意如何得出、产品为什么出场，以及消费者在哪个细节产生共鸣。

**平台观察 → 消费者洞察 → 产品回应 → 沟通主张 → 创意联想 → Core Idea → 场景验证**

## 能用来做什么

- 为一个品牌或产品探索核心创意，并讲清每一步的依据。
- 检查已有 idea 与消费者、产品和品牌之间的联系。
- 为品牌提案整理创意推导话术。
- 把产品资料转成可以拍摄、讲述或参与的创意形式。

## 安装

将仓库克隆到个人 Codex 技能目录。目标文件夹尚未存在时，可以运行

```bash
git clone https://github.com/elisehuang26/core-idea-development.git "$HOME/.codex/skills/core-idea-development"
```

也可以下载仓库，将包含 `SKILL.md` 的 `core-idea-development` 文件夹放到技能目录。

## 使用

可以直接给出任务，并附上现有品牌资料、平台发现或产品 brief

```text
使用 $core-idea-development，为【品牌／产品】推导 Core Idea。
目标人群是【人群】，本次希望解决【传播任务】，主要平台是【平台】。
请说明消费者洞察、产品依据、创意联想和关键执行场景，并检查品牌独占性。
```

已有创意时可以这样使用

```text
使用 $core-idea-development，检查这个 Core Idea 的推导逻辑。
我已有的 idea 是【创意】，产品资料和消费者观察如下【资料】。
请指出有依据的联系、需要验证的假设，以及最值得补强的一步。
```

资料不完整时，技能会说明暂定范围，并标记需要验证的洞察。

## 文件

| 文件 | 内容 |
| --- | --- |
| [SKILL.md](SKILL.md) | 七步推导、证据与假设、创意联想方法、检验标准和提案句式 |
| [agents/openai.yaml](agents/openai.yaml) | 显示名称、简介和调用提示 |
| [references/worked-examples.md](references/worked-examples.md) | 虚构咖啡杯示例，以及爱他美品牌层创意演示 |

爱他美示例演示如何将家长的选奶功课与品牌科研相联系，提出“爱他这件事，我们一起研究”。其中的消费者动机是待验证假设，主推 SKU 尚未限定。该方向为独立创意演示，品牌事实附有公开来源。

## 贡献

欢迎通过 Issue 或 Pull Request 提供改进建议、公开案例和使用反馈。新增案例请交代来源、推导过程及验证程度，使用已获分享授权的素材。

## 许可

本仓库原创内容采用 [MIT License](LICENSE)。引用的品牌资料及相关商标归其权利人所有。
