# 视界Vision--社交媒体网页 
**模仿weibo, twitter类型的社交媒体网站网页设计，暂时不打算涉及数据交互以及后台实现**

## 使用语言
**HTML + CSS + JS（not now）**

## 目前实现的效果展示图
_(updating)_

## 功能目标
1. 左中右页面布局(已完成)
3. 导航栏页面简单跳转(初始功能已完成, 需要进一步增加网页引入导航栏)
4. 修改网页框架模式, 实现复用部分复合组件(PHP? Javascripts? 引入后端java->使用模板引擎Thymeleaf? 暂时没有好想法)
5. 瀑布流内容展示
6. 更多的功能性页面
7. 响应式布局 responsive design

## 设计目标
1. 清晰简洁的页面设计
2. 调整配色. 优化设计方案, 调整元素布局进行视觉强调设计, 删除冗余碍眼的边框
3. 统一的设计风格

## 近期工作
- 优化界面布局(优化边界设计, 调整字体布局, 调整复合组建内子组件的视觉关联设计, 优化色彩搭配方案)
  - 优化边界设计: 使边界不再是一眼就能看出来的硬边界，而是通过细微的组件背景颜色的变化体现出组建与组件之间的分隔, 使组件空间感更加广, 不会被边框压缩。
  - 调整字体布局(学习中): 细致设计字体上的细微差别使内容与内容之间显现出细微的差别，引导用户的视线走向. 
    - px 固定大小 
    - em 相对父级大小 1em = 16px
    - rem 相对html大小 1rem = 16px 
- 响应式设计 (支持动态监控viewport size调整页面, 通过bootstrap实现? 或者直接通过@media实现) 
  - [Coursera 响应式布局 课程 _(可以点击注册后免费旁听-但部分功能不能使用,如测试题)_](https://www.coursera.org/learn/responsivedesign?specialization=web-design)
  - [font-relative-size 参考文章1](https://www.sitepoint.com/understanding-responsive-web-design-how-to-manage-fonts/)
- 增加更多功能性组件, 使页面更加完整饱和

## 配色方案
<!-- https://www.chinavid.com/color.html -->
<!-- #1240AB -->
<!-- 互补色方案 Angle 30 -->
主色 #1240AB	
中深色 #2A4480	
打底深色 #06266F	
中浅色 #4671D5	
亮浅色 #6C8CD5


辅助色A #3914B0

辅助色B亮浅色 #5CCCCC

互补色 #FFAA00
互补色亮浅色 #FFD073

## 像素大小比例计算
1rem = 16px
0.625rem = 10px 
0.9375rem = 15px 
1.25rem = 20px
1.5625rem = 25px 
2.5rem = 40px