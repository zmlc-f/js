
### 常用运算符
#### 加法

- 两侧任何一侧为string：这个时候+为字符串拼接
- 都为number：加法
- 其中之一为NaN：结果为NaN
- null \ undefined \ true \false：先转化为Number，再做加法

```
console.log(null + 1);
-> Number(null) + 1
-> 0 + 1

null+1=1，undefined+1=NaN，1+true=2，1+false=1
```

#### 减法

- 两侧任何一侧为string：先将string转化为Number，再做减法
- 都为number：减法
- 其中之一为NaN：结果为NaN
- null \ undefined \ true \false：先转化为Number，再做减法

#### 隐式类型转换