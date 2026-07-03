---
title: 'Markdown 写作语法参考'
description: '写博客时常用的 Markdown 语法速查，方便随时回来看一眼。'
pubDate: 'Jul 03 2026'
heroImage: '../../assets/blog-placeholder-1.jpg'
---

这是一篇写给自己看的语法参考，把 Astro 博客里常用的 Markdown 写法整理在这里，写文章时忘了就回来翻一下。

## 标题

用 `#` 的数量表示标题级别，一级到六级：

# H1

## H2

### H3

#### H4

##### H5

###### H6

## 段落

直接写文字就是一个段落，段落之间空一行分隔即可。

## 图片

### 语法

```markdown
![替代文字](图片的相对路径或链接)
```

### 效果

![blog placeholder](../../assets/blog-placeholder-about.jpg)

## 引用

### 语法

```markdown
> 这是一段引用。
> **注意** 引用里也可以用 _Markdown 语法_。
```

### 效果

> 这是一段引用。
> **注意** 引用里也可以用 _Markdown 语法_。

## 表格

### 语法

```markdown
| 斜体      | 粗体     | 代码   |
| --------- | -------- | ------ |
| _斜体_    | **粗体** | `代码` |
```

### 效果

| 斜体   | 粗体     | 代码   |
| ------ | -------- | ------ |
| _斜体_ | **粗体** | `代码` |

## 代码块

用三个反引号 ` ``` ` 包裹代码，紧跟语言名可以高亮对应语法，比如 html、javascript、css、bash 等。

````markdown
```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>示例</title>
  </head>
  <body>
    <p>测试</p>
  </body>
</html>
```
````

效果：

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>示例</title>
  </head>
  <body>
    <p>测试</p>
  </body>
</html>
```

## 列表

### 有序列表

```markdown
1. 第一项
2. 第二项
3. 第三项
```

1. 第一项
2. 第二项
3. 第三项

### 无序列表

```markdown
- 项目一
- 项目二
- 项目三
```

- 项目一
- 项目二
- 项目三

### 嵌套列表

```markdown
- 水果
  - 苹果
  - 橙子
  - 香蕉
- 乳制品
  - 牛奶
  - 芝士
```

- 水果
  - 苹果
  - 橙子
  - 香蕉
- 乳制品
  - 牛奶
  - 芝士
