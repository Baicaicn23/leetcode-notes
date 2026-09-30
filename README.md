<div align="center">

# 🌳 LeetCode 刷题笔记

**一道题一个文件夹：题目整理 + 新手向讲解**
*逐行注释 · 正误对照 · 比喻教学*

![已解决](https://img.shields.io/badge/已解决-12_题-brightgreen?style=flat-square) ![简单](https://img.shields.io/badge/简单-6-brightgreen?style=flat-square) ![中等](https://img.shields.io/badge/中等-6-orange?style=flat-square) ![语言](https://img.shields.io/badge/语言-Python_3-blue?style=flat-square) ![笔记](https://img.shields.io/badge/笔记-Obsidian-9C27B0?style=flat-square)

</div>

---

## 📊 刷题清单

### 🗓 2026-09-28 · 数组与字符串

| # | 题目 | 难度 | 核心考点 | 笔记 |
| --- | --- | --- | --- | --- |
| 15 | [三数之和](https://leetcode.cn/problems/three-sum/) | ![中等](https://img.shields.io/badge/中等-orange?style=flat-square) | 排序 + 锚点双指针 + 三重去重 | [📝 讲解](2026-09-28/01-三数之和/三数之和-讲解.md) |
| 3 | [无重复字符的最长子串](https://leetcode.cn/problems/longest-substring-without-repeating-characters/) | ![中等](https://img.shields.io/badge/中等-orange?style=flat-square) | 滑动窗口 + 哈希表 🎬 | [📝 讲解](2026-09-28/02-无重复字符的最长子串/无重复字符的最长子串-讲解.md) |

### 🗓 2026-09-29 · 二叉树专题

| # | 题目 | 难度 | 核心考点 | 笔记 |
| --- | --- | --- | --- | --- |
| 94 | [二叉树的中序遍历](https://leetcode.cn/problems/binary-tree-inorder-traversal/) | ![简单](https://img.shields.io/badge/简单-green?style=flat-square) | 递归遍历 + Morris 穿树 | [📝 讲解](2026-09-29/01-二叉树的中序遍历/二叉树的中序遍历-讲解.md) |
| 104 | [二叉树的最大深度](https://leetcode.cn/problems/maximum-depth-of-binary-tree/) | ![简单](https://img.shields.io/badge/简单-green?style=flat-square) | 自底向上 / 自顶向下 | [📝 讲解](2026-09-29/02-二叉树的最大深度/二叉树的最大深度-讲解.md) |
| 226 | [翻转二叉树](https://leetcode.cn/problems/invert-binary-tree/) | ![简单](https://img.shields.io/badge/简单-green?style=flat-square) | 递归改造：先抄后改 | [📝 讲解](2026-09-29/03-翻转二叉树/翻转二叉树-讲解.md) |
| 101 | [对称二叉树](https://leetcode.cn/problems/symmetric-tree/) | ![简单](https://img.shields.io/badge/简单-green?style=flat-square) | 交叉配对递归 🎬 | [📝 讲解](2026-09-29/04-对称二叉树/对称二叉树-讲解.md) |
| 102 | [二叉树的层序遍历](https://leetcode.cn/problems/binary-tree-level-order-traversal/) | ![中等](https://img.shields.io/badge/中等-orange?style=flat-square) | BFS + 队列分层 | [📝 讲解](2026-09-29/05-二叉树的层序遍历/二叉树的层序遍历-讲解.md) |
| 543 | [二叉树的直径](https://leetcode.cn/problems/diameter-of-binary-tree/) | ![简单](https://img.shields.io/badge/简单-green?style=flat-square) | 树形 DP · 自底向上报链 | [📝 讲解](2026-09-29/06-二叉树的直径/二叉树的直径-讲解.md) |

### 🗓 2026-09-30 · 二叉搜索树专题

| # | 题目 | 难度 | 核心考点 | 笔记 |
| --- | --- | --- | --- | --- |
| 108 | [将有序数组转换为二叉搜索树](https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/) | ![简单](https://img.shields.io/badge/简单-green?style=flat-square) | 分治：中间当根 | [📝 讲解](2026-09-30/01-将有序数组转换为二叉搜索树/将有序数组转换为二叉搜索树-讲解.md) |
| 98 | [验证二叉搜索树](https://leetcode.cn/problems/validate-binary-search-tree/) | ![中等](https://img.shields.io/badge/中等-orange?style=flat-square) | 前序上下界 / 中序递增 | [📝 讲解](2026-09-30/02-验证二叉搜索树/验证二叉搜索树-讲解.md) |
| 230 | [二叉搜索树中第K小的元素](https://leetcode.cn/problems/kth-smallest-element-in-a-bst/) | ![中等](https://img.shields.io/badge/中等-orange?style=flat-square) | 中序报数 + 剪枝 🎬 | [📝 讲解](2026-09-30/03-二叉搜索树中第K小的元素/二叉搜索树中第K小的元素-讲解.md) |
| 199 | [二叉树的右视图](https://leetcode.cn/problems/binary-tree-right-side-view/) | ![中等](https://img.shields.io/badge/中等-orange?style=flat-square) | BFS 名单末位 / DFS 先右后左 | [📝 讲解](2026-09-30/04-二叉树的右视图/二叉树的右视图-讲解.md) |

> 🎬 = 配套互动演示页面（HTML，浏览器直接打开可播放动画）

## 📁 目录结构

```text
YYYY-MM-DD/            ← 按天分组
└── NN-题名/           ← 一题一文件夹
    ├── 题名-题目.md   ← 题面、示例、数据范围
    ├── 题名-讲解.md   ← 比喻思路、关键细节、新手版逐行注释代码
    └── 互动页.html    ← 可选：浏览器打开即播的动画演示
```

## 🙏 致谢

题解思路参考 [Krahets](https://leetcode.cn/u/jyd/) 与 [灵茶山艾府](https://leetcode.cn/u/endlesscheng/) 的力扣题解，每篇讲解的导航处均有原文署名链接；讲解为个人消化后的新手版重写（含"优雅版 vs 新手版"对照表）。

---

<div align="center">

**🚀 持续更新中 · 每解决一题自动推上 GitHub**

</div>
