---
title: ARRAY_FLATTEN
---

将嵌套的数组扁平化，转换成单一层级的数组。

## 语法

```sql
ARRAY_FLATTEN( <array> )
```

## 示例

```sql
SELECT ARRAY_FLATTEN([[1,2], [3,4,5]]);

┌────────────────────────────────────┐
│ array_flatten([[1, 2], [3, 4, 5]]) │
├────────────────────────────────────┤
│ [1,2,3,4,5]                        │
└────────────────────────────────────┘
```
