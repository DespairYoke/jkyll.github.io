---
layout: post
title:  git基础命令记录
catagory: base-command
tags: [base-command]
description: git基础命令记录
---

### tag
#### tag创建
- git tag v1.0
- git tag -a v0.1 -m "version 0.1 released"

### tag提交

- git push origin v1.0   提交具体的tag
- git push origin --tags   提交所有的tag
    
### 删除远程tag

git push origin --delete tag <tagname>