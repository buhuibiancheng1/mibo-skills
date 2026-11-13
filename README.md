# Mibo Skills

在你的 Agent 中使用 Mibo 的 82 项能力：76 个用户入口、6 项内部能力。涵盖内容研究、策划、制作、复盘与画像，成果保存到同一 Mibo 账号。

## 豆包安装

在豆包的技能页面选择「与豆包对话新建技能」，发送：

```text
安装：https://github.com/buhuibiancheng1/mibo-skills
```

技能目录为 `skills/mibo/`，需保留其中全部文件。安装后添加名为 `mibo` 的 HTTP 连接器，服务地址 `https://mibo.zhujunyue.com/mcp`，通过网页登录授权。

## 其他接入入口

| 平台 | 安装 |
| --- | --- |
| DeepSeek Harness | [原生插件](https://mibo.zhujunyue.com/install/deepseek-harness.md) |
| WorkBuddy | [CLI + Skill](https://mibo.zhujunyue.com/install/workbuddy.md) |
| 豆包工作 | [安装教程](https://mibo.zhujunyue.com/tutorials/doubao.html) |
| ChatGPT | [连接 Mibo](https://mibo.zhujunyue.com/install/chatgpt.md) |

首次使用时登录 Mibo 并同意连接，之后直接在当前对话提出需求。

- 帮我提取这个视频的文案。
- 分析这个账号，并给出新的选题方向。
- 结合我的画像，创作三条口播脚本。

[完整功能目录](skills/mibo/references/catalog.md) · [宿主知识与任务资料](skills/mibo/references/host-knowledge.md)

各平台安装文档包含更新和卸载方法。长期知识由宿主管理，Mibo 保存本次任务输入、运行记录及成果。每次视频生成先展示本次预计积分和规格，再由用户本人确认。
