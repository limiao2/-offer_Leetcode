# -offer_Leetcode
剑指offer_Leetcode
| 题号 | 题目 | Leetcode Link | Note|
| ---- |------|--------|---|
|3|数组中重复的数|https://leetcode.com/problems/find-the-duplicate-number/|<ul><li>字典 - 时间O(N),空间O(N)</li><li>排序 - 时间O(NlogN),空间O(1)</li><li>不能用额外空间 - 原地哈希 - 时间O(N), 空间O(1)</li><li>不能改变数组不能用额外空间 - 二分或者linked list cycle - 前者时间O(NlogN),空间O(1)，后者O(N), 空间O(1)</li></ul>|
|3.1|Find All Duplicates in an Array| https://leetcode.com/problems/find-all-duplicates-in-an-array/| 用index这个数组，把数值乘-1|
|4|二维数组中的查找|https://leetcode.com/problems/search-a-2d-matrix/| 转成array然后binary search O(log(MN))|
|4.1|二维数组中的查找 二|https://leetcode.com/problems/search-a-2d-matrix-ii/|找规律，从右上角开始|
|5|替换空格|https://leetcode-cn.com/problems/ti-huan-kong-ge-lcof/|计算几个空格和改变后的字符长度，双指针，O(N)|
|6|从尾到头打印链表|https://leetcode.com/problems/print-immutable-linked-list-in-reverse/| recursion & stack。如果没有时间限制可以无限iterate这个list，找到N-1这个位置的值，O（N**2）|
|6.1|Reverse Linked List|https://leetcode.com/problems/reverse-linked-list/|双指针 prev future|
|7|重建二叉树|<ul><li>https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/</li><li>https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/</li></ul>||
|8|二叉树的下一个节点|<ul><li>https://leetcode.com/problems/populating-next-right-pointers-in-each-node/ </li><li>https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/</li></ul>| 不是一个题，但是leetcode可以用两个pointer来记录leftmost 和 head，然后head一直next。不是perfect binary用三个指针, leftmost, current leve, next level |
|9|用两个栈实现队列|https://leetcode.com/problems/implement-queue-using-stacks/|如何做到O（1）amortized?|
|||||
|||||
|||||
|||||
|||||