# 添加文件等基本操作
1. git add 
2. git status (检查当前情况，注意使用)

# pull保持更新
## pull的示例场景
在 new 分支下更改README文件，假装是别人的分支修改了之后，需要合并到main。 修改完成之后推送推送</br>。
在main下pull先更新仓库，然后new分支做的更改其实main分支没有，因此需要git merge new，这时候两边的文件均一样.