题目链接：[leetcode - 27](https://leetcode-cn.com/problems/remove-element)

教程链接：[小浩算法](https://www.geekxh.com/1.0.%E6%95%B0%E7%BB%84%E7%B3%BB%E5%88%97/005.html)

# 我的解题思路
1. 遍历数组，如果当前元素和要删除元素相同则删除，否则继续遍历
2. 使用append拼接的方式删除，由于append是操作原数组，所以是原地算法
