# DN 武夷山编程工坊

## 目录

1. 第一期 网页制作入门
    1. 第一课 认识网页结构及标签
    2. 第二课 常见标签及文档细读
    3. 第三课 使用云开发环境
    4. 第四课 初识 CSS
    5. 第五课 盒子模型
    6. 第六课 常见布局
    7. 第七课 答疑及其他


## 第一期 网页制作入门

> 🎯目标：制作一个网页（个人简历或兴趣小组页面）
>
> 📅时长：两周

### 第一课 认识网页结构及标签

#### 导入：“编程即命令”思想

#### 网页结构

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <header></header>
  <main></main>
  <footer></footer>
</body>
</html>
```

#### 认识标签

[前端标签小结](https://www.cnblogs.com/stevending1st/p/htmlLabelAll.html)

#### 作业
- 必做：注册 [freeCodeCamp](https://www.freecodecamp.org/)，提交个人主页。
  - 方法：注册后点击头像或通过右上角 `Menu`-> `Profile` 进入个人主页，复制该页面地址提交。
- 选做：尝试完成 [通过创建猫咪相册应用学习 HTML](https://www.freecodecamp.org/chinese/learn/2022/responsive-web-design/#learn-html-by-building-a-cat-photo-app) 。

> **参考资料**
> 1. [MDN](https://developer.mozilla.org/zh-CN/)
> 2. [freeCodeCamp - Legacy Responsive Web Design V8](https://www.freecodecamp.org/chinese/learn/2022/responsive-web-design/#learn-html-by-building-a-cat-photo-app)
> 3. [HTML 标准](https://html.spec.whatwg.org/multipage/#toc-introduction)
> 4. [W3school](https://www.w3school.com.cn/)


### 第二课 常见标签及文档细读

#### 学习方法

read - search - ask

#### 复习标签

#### 阅读常见标签

#### 作业
- 必做：尝试完成 [通过创建猫咪相册应用学习 HTML](https://www.freecodecamp.org/chinese/learn/2022/responsive-web-design/#learn-html-by-building-a-cat-photo-app) 。

> **参考资料**
> 1. [MDN](https://developer.mozilla.org/zh-CN/)
> 2. [freeCodeCamp - Legacy Responsive Web Design V8](https://www.freecodecamp.org/chinese/learn/2022/responsive-web-design/#learn-html-by-building-a-cat-photo-app)
> 3. [HTML 标准](https://html.spec.whatwg.org/multipage/#toc-introduction)
> 4. [W3school](https://www.w3school.com.cn/)

### 第三课 使用云开发环境

#### 华为云开发者空间

1. 安装编辑器

```bash
sudo apt install code
```

#### 码上掘金平台

#### 作业

- 必做：使用 HTML 做一个页面（个人简历或兴趣小组页面）。

### 第四课 初识 CSS

#### 样式表

##### 1. 行内样式表
```html
<p style="color: sienna; margin-left: 20px">
This is a paragraph
</p>
```

##### 2. 内部样式表
```html
<head>
  <style type="text/css">
    body {background-image: url("images/back40.gif");}
  </style>
</head>
```

##### 3. 外部样式表

```html
<head>
    <link rel="stylesheet" type="text/css" href="mystyle.css" />
</head>
```

```css
body {background-image: url("images/back40.gif");}
```

> **优先级** 
>
> 行内样式表 > 内部样式表 > 外部样式表

#### 选择器
##### 1. & 嵌套选择器
```css
.parent-rule {
  /* 父规则的属性 */
  .child-rule {
    /* 子规则的属性 */
  }
}
```

##### 2. 属性选择器
```css
a[title] {
  color: purple;
}

a[href="https://example.org"] {
  color: green;
}
```
##### 3. 类选择器
```css
/* 所有含有 class="spacious" 类的元素 */
.spacious {
  margin: 2em;
}

/* 所有含有 class="spacious" 类的 <li> 元素 */
li.spacious {
  margin: 2em;
}
```

##### 4. ID 选择器
```css
/* id 为“demo”的元素会被选中 */
#demo {
  border: red 2px solid;
}
```

##### 5. 类型选择器（标签选择器）
```css
/* 所有 <a> 元素。*/
a {
  color: red;
}
```
##### 6. 通配选择器
```css
* {
  color: red;
}
```

> **常见选择器优先级**
>
> ID 选择器 > 类选择器 > 类型选择器 > 通配选择器

#### 作业
- 必做：尝试完成 [通过创建咖啡店菜单学习基础 CSS](https://www.freecodecamp.org/chinese/learn/2022/responsive-web-design/#learn-basic-css-by-building-a-cafe-menu) 。

> **参考资料**
> 1. [选择器 - MDN](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Reference/Selectors)
> 2. [引入 CSS - MDN](https://www.w3school.com.cn/css/css_shiyong.asp)
> 3. [通过创建咖啡店菜单学习基础 CSS](https://www.freecodecamp.org/chinese/learn/2022/responsive-web-design/#learn-basic-css-by-building-a-cafe-menu)

### 第五课 盒子模型

#### 作业
- 必做：尝试完成 [通过创建咖啡店菜单学习基础 CSS](https://www.freecodecamp.org/chinese/learn/2022/responsive-web-design/#learn-basic-css-by-building-a-cafe-menu) 。

> **参考资料**
> 1. [CSS 盒子模型 - 菜鸟教程](https://www.runoob.com/css/css-boxmodel.html)
> 2. [盒模型 - MDN](https://developer.mozilla.org/zh-CN/docs/Learn_web_development/Core/Styling_basics/Box_model)
> 3. [通过创建咖啡店菜单学习基础 CSS](https://www.freecodecamp.org/chinese/learn/2022/responsive-web-design/#learn-basic-css-by-building-a-cafe-menu)

### 第六课 常见布局

### 第七课 答疑及其他


### 致谢

- 感谢 [gstar.huqi.host](https://gstar.huqi.host/) 为本次活动提供云资源及技术支持。

- 感谢 [开源市集](https://open-source-bazaar.github.io/) 深夜自习室为本次活动提供技术支持。

- 感谢 DN 武夷山提供本次活动场地。

