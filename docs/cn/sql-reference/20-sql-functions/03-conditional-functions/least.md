---
title: LEAST
---

从一组值中返回最小值。

## 语法

```sql
LEAST(<value1>, <value2> ...)
```

## 示例

```sql
SELECT LEAST(5, 9, 4);

┌────────────────┐
│ least(5, 9, 4) │
├────────────────┤
│              4 │
└────────────────┘
```