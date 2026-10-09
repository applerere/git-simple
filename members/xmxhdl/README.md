## 第一次 Git 实验总结
1. `git add` 的作用是:把工作区修改添加到暂存区 (stage)，为 commit 做准备，告诉 git 哪些变更要提交。
2. `git commit` 的作用是:把暂存区的改动保存到本地版本库，生成一条 commit 记录，只存在你的电脑本地。
3. 本次实验中 `git restore notes.md` 的作用是:撤销工作区还没有 add 的修改，把 notes.md 恢复成暂存区里的版本，丢弃临时新增的文字。
4. `commit` 与 `push` 的区别是:`commit`是本地生成版本快照，只在本机；`push`是把本地已经 commit 好的提交上传推送到远程服务器仓库。
