# reading-archive
読書ログ

書籍ごとに Markdown ファイルを作成し、以下のフォーマットで記録する。  
将来的にDBとして扱えることを前提に構造化している。

Rules
 - 各書籍は 1冊につき1ファイル
 - ファイル名は 書籍タイトル.md
 - tags は 最大3個まで
 - finished は YYYY-MM-DD 形式

---

## Template

```markdown
実際にmd内に記載するのは↓から
---
title: タイトル
author: 著者名
volume:            # 上 / 下 / 1 / 2 など（なければ空）
finished: YYYY-MM-DD
published: YYYY-MM-DD
country: 国
tags:
  - タグ
  - タグ
  - タグ
---

## summary
要約

## impression
感想

## quotes
引用テキスト
