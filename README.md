# 英语学习知识库

这是一个以“看懂工作长句和技术文档”为主要目标的长期学习库。学习方式不是逐词翻译，而是先识别句子结构，再理解完整意思。

## 使用入口

- [当前学习上下文](CONTEXT.md)
- [学习路线](SYLLABUS.md)
- [重点词汇](knowledge/vocabulary.md)
- [语法句式](knowledge/grammar-patterns.md)
- [常见错误](knowledge/common-mistakes.md)
- [每日课程](daily/)
- [技术材料说明](materials/inbox/README.md)
- [阅读笔记](materials/reading-notes/README.md)

## 固定学习流程

1. 每天练习三句，一次只处理一句。
2. 先找主句、从句、完整谓语、修饰关系和时间顺序。
3. 再给出自然中文意思，避免逐词硬译。
4. 课程结束后更新每日记录、词汇、语法、错题和学习进度。
5. 检查变更后创建一次 Git 提交，并同步到 GitHub 远程仓库。

## Git 仓库

- 本地分支：`main`
- 远程仓库：`https://github.com/Cyclones-Y/English-Learning.git`
- 上游分支：`origin/master`
- 每天三句全部完成后统一提交并推送，不对未完成课程创建零散提交。
- 禁止强制推送；遇到远程历史变化时先拉取并检查差异。

## 技术资料

Markdown 和纯文本资料可以直接纳入 Git。PDF、Office、图片、音视频和压缩包可以放入 `materials/inbox`，但默认不进入 Git 历史；从这些资料提炼出的阅读笔记会被正常跟踪。
