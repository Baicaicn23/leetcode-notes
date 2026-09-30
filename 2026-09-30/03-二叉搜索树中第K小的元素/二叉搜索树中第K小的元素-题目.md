---
tags:
  - leetcode
  - 树
  - 二叉搜索树
  - 中序遍历
  - 深度优先搜索
aliases:
  - Kth Smallest Element in a BST
  - 二叉搜索树中第K小的元素
difficulty: 中等
date: 2026-09-30
status: 已解决
---

# 230. 二叉搜索树中第 K 小的元素

![LeetCode](https://img.shields.io/badge/LeetCode-230-black?style=flat-square&logo=leetcode&logoColor=white) ![难度](https://img.shields.io/badge/难度-中等-orange?style=flat-square) ![状态](https://img.shields.io/badge/状态-已解决-brightgreen?style=flat-square)

> [!info] 导航
> 🔗 [力扣原题](https://leetcode.cn/problems/kth-smallest-element-in-a-bst/) ｜ 📝 配套讲解：[[二叉搜索树中第K小的元素-讲解]] ｜ 📅 2026-09-30

## 📖 题目描述

给定一个二叉搜索树的根节点 `root`，和一个整数 `k`，请你设计一个算法查找其中第 `k` 小的元素（`k` 从 1 开始计数）。

> [!warning] 关键前提是"树已经是 BST"
> 左小右大的性质是**白给的**——不用验证、不用排序，想清楚"BST 的有序性藏在哪种走法里"就赢了一半。另外 `k` 从 1 数起：第 1 小 = 全树最小值。

## 🧪 示例

> [!example] 示例 1
> **输入**：`root = [3,1,4,null,2]`，`k = 1`
> **输出**：`1`
>
> ```text
>   3
>  / \
> 1   4
>  \
>   2
> ```
>
> 全树从小到大排队：1、2、3、4 → 第 1 小是 `1`。

> [!example] 示例 2
> **输入**：`root = [5,3,6,2,4,null,null,1]`，`k = 3`
> **输出**：`3`
>
> ```text
>     5
>    / \
>   3   6
>  / \
> 2   4
> /
> 1
> ```
>
> 从小到大排队：1、2、3、4、5、6 → 第 3 小是 `3`。

## 📏 数据范围

| 约束 | 值 | 暗示 |
| --- | --- | --- |
| 节点数 n | `1 ~ 10^4` | 至少一个节点；`k` 保证合法，不用处理越界 |
| k | `1 <= k <= n` | 从 1 计数，第 1 小就是最小值 |
| 节点值 | `0 <= Node.val <= 10^4` | 无特殊 |
| 进阶 | BST 频繁插入/删除 + 频繁查第 k 小 | 高频面试追问，解法要给树"记账"——讲解文末有思路 |

---

⬅️ 讲解见 [[二叉搜索树中第K小的元素-讲解]]
