# Markdown 常用语法

## 一、标题

使用 `#` 符号表示标题，支持 1-6 级标题：

```markdown
# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题
```

## 二、文本格式

### 加粗

```markdown
**这是加粗文本**
```

### 斜体

```markdown
_这是斜体文本_
```

### 加粗斜体

```markdown
**_这是加粗斜体文本_**
```

### 删除线

```markdown
~~这是删除线文本~~
```

## 三、列表

### 无序列表

```markdown
- 列表项 1
- 列表项 2
  - 子列表项 1
  - 子列表项 2
```

### 有序列表

```markdown
1. 列表项 1
2. 列表项 2
   1. 子列表项 1
   2. 子列表项 2
```

## 四、链接

### 普通链接

```markdown
[百度](https://www.baidu.com)
```

### 图片链接

```markdown
![VuePress Logo](/img/logo.png)
```

## 五、代码

### 行内代码

```markdown
`console.log('Hello World')`
```

### 代码块

````markdown
```javascript
function hello() {
  console.log("Hello World");
}
```
````

````

## 六、引用

```markdown
> 这是引用文本
> 可以换行继续引用
````

## 七、表格

```markdown
| 姓名 | 年龄 | 性别 |
| ---- | ---- | ---- |
| 张三 | 20   | 男   |
| 李四 | 25   | 女   |
```

## 八、分割线

```markdown
---
```

## 九、任务列表

```markdown
- [x] 已完成任务
- [ ] 未完成任务
```
