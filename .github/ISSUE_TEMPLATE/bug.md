---
name: 安装和使用异常
about: 请务必首先阅读首页【常见问题】中的内容，尤其是其中【更多问题】部分内容，否则我可能不会回答你的任何问题。
title: ''
labels: ''
assignees: ''

---

*如果你是Linux新手，请严格按照下面的模板来提问，你见过去公安局报案直接说“我钱丢了”但是不说时间地点经过的？请互相尊重，不要一上来什么信息都没有直接贴问题。*
*如果你对Linux比较熟悉，并且明白问题的根本原因出在哪里，甚至做了简单的复现，那自由表述即可，不必拘泥下面的模板。*

**系统版本**
通过`lsb_release -a`查看。

**桌面类型**
Gnome？KDE？不清楚的话通过`echo $XDG_CURRENT_DESKTOP`查看。

**软件源列表**
`grep -rn '^\s*deb ' --include '*.list' /etc/apt/`的输出。

**问题描述**
问题是怎么产生的，有什么表现，如何复现。