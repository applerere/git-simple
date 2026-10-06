Git 初次实验总结

## 第一次 Git 实验总结
1. `git add` 的作用是:
把工作区的修改加入暂存区，为commit提交做准备，还没有存入版本库。
2. `git commit` 的作用是:
将暂存区的改动保存生成本地版本库的提交记录，只保存在本地，不上传远程。
3. 本次实验中 `git restore notes.md` 的作用是:
撤销工作区没有add的修改，把notes.md恢复到上一次提交的状态，删掉临时新增文字。
4. `commit` 与 `push` 的区别是:
commit保存改动到**自己电脑本地Git仓库**；push把本地提交上传推送到GitHub远程服务器。
