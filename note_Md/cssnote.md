
## bfc（**Block Formatting Context**）
[原文链接](https://blog.csdn.net/sqLeiQ/article/details/125261564)
> 实现bfc方法
> 1.**body根元素**
> 2.**设置浮动，不包括none**
> 3.**设置定位，absoulte或者fixed**
> 4.**行内块显示模式，inline-block**
> 5.**设置overflow，即hidden，auto，scroll**
> 6.**表格单元格，table-cell**
> 7.**弹性布局，flex**

> 解决部分问题  
> 1.**解决外边距的塌陷问题(垂直塌陷)**
> 2.**利用BFC解决包含塌陷**
> 3.**清除浮动**
> 4.**BFC可以阻止标准流元素被浮动元素覆盖**

## 相对单位大小
> |单位|相对于|
> |---|---|
> |`em`|在 font-size 中使用是相对于父元素的字体大小，在其他属性中使用是相对于自身的字体大小，如 width|
> |`ex`|字符“x”的高度|
> |`ch`|数字“0”的宽度|
> |`rem`|根元素的字体大小|
> |`lh`|元素的 line-height|
> |`vw`|视窗宽度的 1%|
> |`vh`|视窗高度的 1%|
> |`vmin`|视窗尺寸的 1%|
> |`vmax`|视图寸的 1%||


<!--stackedit_data:
eyJoaXN0b3J5IjpbMzA2Mjc2MjkyLDEwNzU5MzQ3NDcsLTIxMz
M2MDkxMDMsLTEwOTA5NTg5NDBdfQ==
-->