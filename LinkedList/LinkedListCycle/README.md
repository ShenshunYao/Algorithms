# Linked List Cycle I（环形链表）

**LeetCode 142**

- [英文版](https://leetcode.com/problems/linked-list-cycle/)

- [中文版](https://leetcode-cn.com/problems/linked-list-cycle/)

## 题目
给定一个链表，判断链表中是否有环。

为了表示给定链表中的环，我们使用整数 pos 来表示链表尾连接到链表中的位置（索引从 0 开始）。 如果 pos 是 -1，则在该链表中没有环。

示例 1：
```
输入：head = [3,2,0,-4], pos = 1
输出：true
解释：链表中有一个环，其尾部连接到第二个节点。
```

示例 2：
```
输入：head = [1,2], pos = 0
输出：true
解释：链表中有一个环，其尾部连接到第一个节点。
```

示例 3：
```
输入：head = [1], pos = -1
输出：false
解释：链表中没有环。
```

进阶：

你能用 O(1)（即，常量）内存解决此问题吗？

## 思路
<details>
<summary>点击展开</summary>
快慢指针，快指针每次前进两步，慢指针每次前进一步。如果链表中不存在环，则快指针先到达链表尾；若存在环，则快慢指针总会相遇。
</details>

## 代码实现
| C | C++ | Java | Objective-C | Swift | Python | JavaScript | Go | PHP |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 🤔 | [😀](./LinkedListCycle.cpp) | [😀](./LinkedListCycle.java) | 🤔 | 🤔 | [😀](./LinkedListCycle.py) | 🤔 | [😀](./linked_list_cycle.go) | 🤔 |

