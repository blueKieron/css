## bfc（**Block Formatting Context**）
> 实现bfc方法
> 1.**body根元素**
> 2.**设置浮动，不包括none**
> 3.**设置定位，absoulte或者fixed**
> 4.**行内块显示模式，inline-block**
> 5.**设置overflow，即hidden，auto，scroll**
> 6.**表格单元格，table-cell**
> 7.**弹性布局，flex**

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

> *percent: 如果将元素的字体大小设置为百分比，那么它将是元素父元素字体大小的百分比。如果使用百分比作为宽度值，那么它将是父值宽度的百分比*
> *使用百分比作为元素外边距（margin）或填充（padding）的单位时，值是以包含块的**内联尺寸**进行计算的，也就是元素的水平宽度。在我们的示例中，所有的外边距或填充都是宽度的 10%。请记住一个事实，当你使用百分比作为元素外边距或填充的单位时，你将得到一个相同尺寸的外边距或填充。*

> 当使用 `object-fit` 时，替换元素可以以多种方式被调整到合乎盒子的大小。*cover fill contain*
> 在对替换元素使用各种 CSS 布局时，你可能会发现他们的表现方式与其他元素有一些细节>上的差异。例如，flex 或者 grid 布局中，默认情况下元素会被拉伸到充满整块区域。但是
 图像不会被拉伸，而会对齐到网格区域或者弹性容器的起始处。
> ``` css
>  `为了强制图像拉伸，以充满其所在的网格单元，你必须做类似于下面的事情：`
> ``` css
> img {
>  width: 100%;
>  height: 100%;
>}
> ```


## EMMENT语法
![image](https://user-images.githubusercontent.com/48239113/222026982-ac9ccb0a-0300-4ea6-bfa8-6a0e495dbe05.png)

## snipaste工具
![image](https://user-images.githubusercontent.com/48239113/222028021-8c318d8f-0f90-41e1-b22a-44b0543bba7d.png)

## 盒子宽度
![image](https://user-images.githubusercontent.com/48239113/222028071-82a3ec8f-46f9-432f-8ee5-957848f1282c.png)

## 解决嵌套元素垂直外边距塌陷问题
![image](https://user-images.githubusercontent.com/48239113/222028100-69046d45-98db-4b5c-b50e-67fc8c7f707e.png)

## 清除浮动
![image](https://user-images.githubusercontent.com/48239113/222028134-37f1befa-c45a-422e-b507-947baffad638.png)

## CSS属性书写顺序
![image](https://user-images.githubusercontent.com/48239113/222028159-40c13430-7158-4094-b92d-d226c22483c2.png)

## 相对定位
![image](https://user-images.githubusercontent.com/48239113/222028202-fd945b7e-2a68-4f5d-93eb-35d4faa1dc30.png)

## 绝对定位
![image](https://user-images.githubusercontent.com/48239113/222028212-709fce9f-990c-4859-99a2-42ec80279f33.png)

## z-index属性只有定位的盒子才有这个属性

## 绝对定位、相对定位与浮动的特殊性
![image](https://user-images.githubusercontent.com/48239113/222028235-3eca2757-004b-47aa-89ec-a15249488094.png)

## icomoon
```
1. 网站上选择内容并下载，加入font文件夹，cssStyle样式
2. 复制图标内容 加font-family属性
（追加图标: 选selection.json文件上传，追加后下载替换）
```
## 三角形
![image](https://user-images.githubusercontent.com/48239113/222028264-db9c7d0f-4ce8-47ab-b4e1-013862e7b9a8.png)

## 三角形 表格轮廓 大小拖动
![image](https://user-images.githubusercontent.com/48239113/222028279-120e946f-b0da-40e1-9137-026a9e6f0f3b.png)
![image](https://user-images.githubusercontent.com/48239113/222028296-4caf747e-fda2-44d9-a884-fa182e74a083.png)

## vertical-align
![image](https://user-images.githubusercontent.com/48239113/222028320-9339e210-26f2-49ff-a6bd-b59f77c8a49a.png)
![image](https://user-images.githubusercontent.com/48239113/222028336-f60b4958-6f1a-4064-bb17-fd0415ca86cd.png)

## 省略号
![image](https://user-images.githubusercontent.com/48239113/222028359-677e3343-7c18-4c11-a5f0-8164ca1f066e.png)
![image](https://user-images.githubusercontent.com/48239113/222028380-d88dde26-1f1c-499a-88bd-05d1b77a757a.png)

## 类选择器 伪类选择器 属性选择器权重一样
## 元素选择器 伪元素选择器权重一样

## css3新属性
![image](https://user-images.githubusercontent.com/48239113/222310368-ac5d0958-39ad-45de-a90e-ee481cfa5a9f.png)
![image](https://user-images.githubusercontent.com/48239113/222310411-d2df5c66-f8d5-4164-b356-21fa1beee39b.png)
![image](https://user-images.githubusercontent.com/48239113/222310429-4c2ffd1e-ec27-4f31-b5d0-4ea95b49fb15.png)
![image](https://user-images.githubusercontent.com/48239113/222310448-4c1baff1-b0b6-4d4e-8032-511f897954a8.png)
![image](https://user-images.githubusercontent.com/48239113/222310481-e2a6264a-70bc-41b0-bb2e-907999271e78.png)
![image](https://user-images.githubusercontent.com/48239113/222310498-9650454f-c21a-4c48-80d7-124e48898382.png)
![输入图片说明](https://raw.githubusercontent.com/blueKieron/drawingBed/main/notes/2023-03-03-cssnote/nGXkPgS2mxQv6H3r.png)
![输入图片说明](https://raw.githubusercontent.com/blueKieron/drawingBed/main/notes/2023-03-03-cssnote/TgJniifFuqbXV42p.png)
![输入图片说明](https://raw.githubusercontent.com/blueKieron/drawingBed/main/notes/2023-03-03-cssnote/WiUvzru519cEk4b5.png)
![输入图片说明](https://raw.githubusercontent.com/blueKieron/drawingBed/main/notes/2023-03-03-cssnote/nR5CFU6TpUG8hZWF.png)
![输入图片说明](https://raw.githubusercontent.com/blueKieron/drawingBed/main/notes/2023-03-03-cssnote/XOjLSaLLuOwEQTz2.png)
![输入图片说明](https://raw.githubusercontent.com/blueKieron/drawingBed/main/notes/2023-03-03-cssnote/PvMasIMMDvRGho1Z.png)      
![输入图片说明](https://raw.githubusercontent.com/blueKieron/drawingBed/main/notes/2023-03-03-cssnote/woQYej3IO6NL5VpM.png)

## 私有前缀
![输入图片说明](https://raw.githubusercontent.com/blueKieron/drawingBed/main/notes/2023-03-03-cssnote/54Tba8UCAEhKofca.png)












































<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxMDk2NzM1NDQsMTUyNzg0ODk3MCwxMD
I2Mjg4ODQyLDEwNzk5MTUyOTUsODgwNTQ1MDkzLC0xNDAyNDIy
NDIwLC0xNTA4Mjk4MDA0LC0yMDkwNTM4MjU3LDE3ODcyNTc4Nj
UsOTIyNzc4NjMsMTczOTQ5Mjk5MCwtMjA2MDk2NjQ5NCwtNjcw
MzA4NDQ5LC02ODYzNjg4ODgsLTE1MTIyMDA1MTgsNjExMDM1Nj
g4LDYxMTAzNTY4OCwxNzMxMTAyNTM1LDYzMzU1Mjc0NSw4NjQ0
MTQ5NzRdfQ==
-->