# 标签
## 栏目标签
### 使用方式

```
<section></section>
```

### 属性列表

属性|说明|类型|默认值
---|---|---|---
list|获取非分页栏目列表，优先级大于page|boolean |false
page|获取分页栏目列表|boolean|false
size|获取{size}条栏目|int|list下默认获取全部，分页状态下默认获取上下文中的值
current|获取第{current}页栏目|int|list下默认获取全部页，分页状态下默认获取上下文中的值
pid|根据父id获取栏目|long|-
code|根据code获取栏目|string|-
id|根据id获取栏目|long|-
show|获取展示的栏目|boolean|true
top|仅获取置顶的栏目|boolean|默认获取全部
as|标签内部使用数据前缀，默认为data，如：data.id|string|data
pcode|通过父栏目编码获取栏目|string|-
exclude|排除某个id的栏目|string|-

### 介绍

1. 默认获取单条数据，使用list或page属性时获取多条数据。
2. 默认排序以置顶>序号作为排序条件。


## 文章标签

### 使用方式

```
<article></article>
```

### 属性列表

属性|说明|类型|默认值
---|---|---|---
list|获取非分页文章列表，优先级大于page|boolean |false
page|获取分页文章列表|boolean|false
size|获取{size}条文章|int|list下默认获取全部，分页状态下默认获取上下文中的值
current|获取第{current}页文章|int|list下默认获取全部页，分页状态下默认获取上下文中的值
code|根据code获取文章|string|-
id|根据id获取文章|long|-
show|获取展示的文章|boolean|true
top|仅获取置顶的文章|boolean|默认获取全部
scode|根据栏目code获取文章|string|-
sid|根据栏目id获取文章，优先级大于scode|long|-
as|标签内部使用数据前缀，默认为data，如：data.id|string|data
exclude|排除某个id的文章|string|-


## 字典
### 使用方式

```
<dict></dict>
```

### 属性列表

属性|说明|类型|默认值
---|---|---|---
list|获取非分页字典列表，优先级大于page|boolean |false
page|获取分页字典列表|boolean|false
size|获取{size}条字典|int|list下默认获取全部，分页状态下默认获取上下文中的值
current|获取第{current}页字典|int|list下默认获取全部页，分页状态下默认获取上下文中的值
type|根据type获取字典|string|-
name|根据name获取字典|string|-
id|根据id获取字典|long|-
as|标签内部使用数据前缀，默认为data，如：data.id|string|data
