---
title: ARRAY_CONCAT
---

将两个数组连接起来。

## 语法

```sql
ARRAY_CONCAT( <array1>, <array2> )
```

## 示例

```sql
SELECT ARRAY_CONCAT([1, 2], [3, 4]);

┌──────────────────────────────┐
│ array_concat([1, 2], [3, 4]) │
├──────────────────────────────┤
│ [1,2,3,4]                    │
└──────────────────────────────┘
```
