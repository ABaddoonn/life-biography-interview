# 人生传记与口述史采访

一个用于人生传记、长者口述史与家族回忆录的 Hermes Skill。先梳理人生全貌，再选故事深入；一次一问，按轮收尾，整理时间线与书稿。尊重受访者的隐私，避免编造记忆、原话和场景。

## 使用

安装后对助手说：“使用人生传记 Skill，采访我。”也可以提供已有访谈记录，让它接着整理或写稿，不必重新问一遍。

流程：**确定范围 → 梳理人生阶段 → 选择少量故事补访 → 整理时间线与章节 → 核对后成稿。**

未指定时，本轮安排约 30 分钟、约 8 个主问题，含追问和澄清最多 12 个问题；任一上限达到就先收尾。这是本 Skill 的默认安排，不是行业标准，也不保证一轮写完完整传记。想不起来、不想讲的部分可以跳过。短版和完整传记按材料与本人意愿分别安排，不无限延长采访。

## v1.1.0 改进

- 先搭人生全貌，不再默认从模糊的幼年记忆开始。
- 已答过不重复问；听不懂就换简单问法，仍不懂则跳过。
- 同一故事只补必要细节，不逐件盘问日常杂事。
- 接受纠正并更新记录，不把推断写成用户经历。
- 明确每轮上限与阶段成果，用户询问耗时或疲倦时先停下来。
- 公开仓库只保存通用方法和虚构检查场景，不保存私人访谈。

## 安装

安装到 Hermes：

```bash
hermes skills install ABaddoonn/life-biography-interview/skills/life-biography-interview
```

也可以在 GitHub 页面选择 **Code → Download ZIP**，下载后将 `life-biography-interview` 文件夹放入 Hermes 的 `skills/communication/` 目录。

## 内容

本仓库只包含一个 Skill：

- `skills/life-biography-interview/SKILL.md`
- `skills/life-biography-interview/references/interview-checks.md`：虚构回归场景及检查要求

## 许可

本项目采用 MIT License，详见 [LICENSE](LICENSE)。这允许他人使用、修改、分发和商用，但需保留版权和许可声明。
