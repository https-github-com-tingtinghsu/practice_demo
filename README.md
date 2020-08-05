# Ace Team Git Commit 原則

- 1. 實作功能務必先開新分支 `git checkout -b 你的分支名稱`。
  - 每次修改完送的`Pull Request`不要切的太大顆。
  - 每次`Pull Request`請每一位組員們看過，留下comment。
  - 最後一位comment的人負責`git merge`。

- 2. 如果有其他人送的`Pull Request`已經被`git merge`進主分支，請常常`git pull`，讓你的本地repo盡量跟遠端`origin/master`同步。

- 3. 如果修改的部分和遠端`origin/master`相差太多，請善用`git rebase`功能！
  - 先`git pull`，讓你的本地repo跟遠端同步。
  - 切換`HEAD`到`origin/master`
  - 再把你修改的那一段`git rebase`到遠端上。

- 待討論事項：可考慮開一個`develop`分支
![](https://i.imgur.com/oFbBeZe.png)