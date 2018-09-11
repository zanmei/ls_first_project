Git is a version control system.
Git is free software
git is studing
再次挑战
据说执行add命令是往工作暂存区放最后commit是全部上传到master分支上面去
这一次学习说git管理的是修改而不是文件
add之后再提交看看status
咦，怎么第二次的修改没有被提交？

别激动，我们回顾一下操作过程：

第一次修改 -> git add -> 第二次修改 -> git commit

你看，我们前面讲了，Git管理的是修改，当你用git add命令后，
在工作区的第一次修改被放入暂存区，准备提交，但是，在工作区的第二次修改并没有放入暂存区，
所以，git commit只负责把暂存区的修改提交了，也就是第一次的修改被提交了，第二次的修改不会被提交。
哈哈哈哈哈哈哈哈哈