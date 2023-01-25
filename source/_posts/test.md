---
title: test
date: 2023-01-24 00:34:54
tags:
---
This is a test file created by Cao Zheyu.



```mermaid
sequenceDiagram
	participant Cao
	participant CaoGithub
	participant Chen
	participant ChenGithub
	Cao->>CaoGithub:创建
	CaoGithub->>ChenGithub:fork
	loop 修改
		Chen->>ChenGithub:push
		ChenGithub->>Chen:pull
	end
	ChenGithub-->>Cao:pull request
	Cao->>CaoGithub:agree and pull
```

