###  GIT学习笔记

[我的仓库]:https://github.com/HN7479?tab=repositories

---

#### 我所了解的GIT

Git 是一个分布式版本控制系统，版本控制系统简单说就是它可以记录文件的每一步改动并且能够让你非常方便的将多个人的文件内容合并到一起，分布式就是指每一份代码仓库都会保留完整的文件和历史记录。Git 最初由 Linus 创造，目前应用最广泛的领域就是代码开发。**git 保存的不是文件而是对文件的修改**

---



#### 我学到的命令

| 命令                           | 执行的操作                                                   |
| ------------------------------ | ------------------------------------------------------------ |
| pwd                            | 用于显示当前目录                                             |
| git init                       | 把当前目录变成Git可以管理的仓库                              |
| git add 文件名                 | 把文件提交到暂存区                                           |
| git commit -m "本次提交的说明" | 将暂存区的文件提交进仓库                                     |
| git status                     | 让我们掌握仓库当前的状态                                     |
| git diff                       | （前提是git status告诉我们有文件被修改了）查看文件被修改的内容 |
| git log                        | 显示从最近到最远的提交日志                                   |
| git reset --hard 版本代码      | 将当前版本回退到之前的某个版本                               |
| cat 文件名                     | 查看文件内的内容                                             |
| git reflog                     | 查看历史命令                                                 |
| git checkout -- file           | 丢弃工作区的修改                                             |
| rm 文件名                      | 删除文件                                                     |
| git rm 文件名                  | 从版本库里删除该文件                                         |
| git push origin master         | 把本地master分支最新修改推送至GitHub                         |
| git clone                      | 克隆本地库                                                   |
| git checkout/switch 分支名     | 切换到分支                                                   |
| git merge 分支名git            | 合并指定分支到当前分支                                       |
| git remote                     | 查看远程库信息                                               |

### 学习感悟

由于没看到群里的任务昨天才开始学习，但是只要肯学还是能学到东西的，虽然还没有学完但是我基本弄懂了git这个软件的妙用了，学习途中也遇到了许多问题比如远程库的创建，但是经过不断地百度看视频最终还是解决了，同时我也对github了解的更加深入了，我相信只要持之以恒，没有什么困难是打败不了的！