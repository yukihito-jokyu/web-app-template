---
allowed-tools: Bash(git add:*), Bash(git status:*), Bash(git commit:*)
description: gitのコミット作成タスク
---

## Context

- Current git status: !`git status`
- Current git diff (staged and unstaged changes): !`git diff HEAD`
- Current branch: !`git branch --show-current`
- Recent commits: !`git log --oneline -10`
- コミットメッセージは日本語で作成してください。
- コミットメッセージのテンプレートは @.commit-template を参照してください。

## Your task

ファイルごとにコミットを作成する。
