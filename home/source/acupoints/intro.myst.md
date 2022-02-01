# 穴位

## 十二经络

```{figure} assets/img/2022-01-13-11-58-09.png
---
name: 背面经络
---

背面经络
```

```{figure} assets/img/assets/img/2022-01-13-11-58-09.png.png
---
name: 侧面经络
---

侧面经络
```


```{figure} assets/img/2022-01-13-12-00-27.png
---
name: 正面经络
---

正面经络
```

```{list-table} 十二经汇总
---
header-rows: 2
---
* - 手/足
  - 阳
  - 阳
  - 阳
  - 阴
  - 阴
  - 阴
* - 手/足
  - 阳明
  - 太阳
  - 少阳
  - 太阴
  - 少阴
  - 厥阴
* - 手
  - [大肠经](大肠经/intro)
  - [小肠经](小肠经/intro)
  - [三焦经](三焦经/intro)
  - [肺经](肺经/intro)
  - [心经](心经/intro)
  - [心包经](心包经/intro)
* - 足
  - [胃经](胃经/intro)
  - [膀胱经](膀胱经/intro)
  - [胆经](胆经/intro)
  - [脾经](脾经/intro)
  - [肾经](肾经/intro)
  - [肝经](胆经/intro)
```

### 十二经流柱


```{uml}
state 手太阴肺经 
state 手阳明大肠经
state 足阳明胃经 
state 足太阴脾经
state 手少阴心经 
state 手太阳小肠经
state 足太阳膀胱经
state 足少阴肾经
state 手厥阴心包经
state 手少阳三焦经
state 足少阳胆经
state 足厥阴肝经

手太阴肺经 -right-> 手阳明大肠经
手阳明大肠经 -right> 足阳明胃经 
足阳明胃经 -> 足太阴脾经
足太阴脾经 -> 手少阴心经 
手少阴心经 ->  手太阳小肠经
手太阳小肠经 -> 足太阳膀胱经

足太阳膀胱经 -> 足少阴肾经
足少阴肾经 -> 手厥阴心包经
手厥阴心包经 -> 手少阳三焦经
手少阳三焦经 -> 足少阳胆经
足少阳胆经 -> 足厥阴肝经
足厥阴肝经 -> 手太阴肺经
```

## 经络索引

```{toctree}
---
maxdepth: 1
caption: 经络索引
---

督脉/intro
任脉/intro

肺经/intro
大肠经/intro
膀胱经/intro
肝经/intro
胆经/intro
脾经/intro
三焦经/intro
肾经/intro
胃经/intro
小肠经/intro
心经/intro
心包经/intro

带脉/intro
冲脉/intro
阴跷脉/intro
阴维脉/intro
```

## 基本概念

### 具体实践

```{toctree}
---
maxdepth: 1
---

取穴配伍
得气
moxibustion/intro
```

### 奇经八脉

```{toctree}
---
maxdepth: 1
---

八脉交会穴
```

### 常用歌诀

```{toctree}
---
maxdepth: 1
---

玉龙歌
```