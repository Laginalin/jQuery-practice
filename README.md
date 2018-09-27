# jQuery-practice
jQuery练习项目

## 轮播图
1. 呼吸轮播图：
    * 呼吸轮播图的布局要点：
        * 存放图片的list应该重叠在一起，图片容器设置相对定位，li元素设置绝对定位
    * 点击 [demo](https://laginalin.github.io/jQuery-practice/carousel/%E5%91%BC%E5%90%B8%E8%BD%AE%E6%92%AD%E5%9B%BE.html) 查看效果
2. 滚动轮播图：
    * 滚动轮播图的布局要点：
        * 图片应该在一行显示，同时父元素的宽度应该足够宽
        * 图片容器的宽度为一张图片的宽度，将overflow设置为hidden
        * 要有不间断滚动的效果，应该有一张“假图片”，来实现向右拉动，然后通过设置样式实现将“真图”瞬间移动的效果
    * 点击 [demo](https://laginalin.github.io/jQuery-practice/carousel/%E6%BB%9A%E5%8A%A8%E8%BD%AE%E6%92%AD%E5%9B%BE.html) 查看效果
3. 间歇效果：
    * 间歇效果的布局要点：
        * 与滚动轮播图类似，只是图片不是一行显示，而是在列显示，因此父元素的高度应该足够高
    * 点击 [demo](https://laginalin.github.io/jQuery-practice/carousel/%E9%97%B4%E6%AD%87%E6%95%88%E6%9E%9C.html) 查看效果
4. 手风琴效果：
    * 手风琴效果的布局要点：
        * 图片绝对定位，设置不同的left值来达到堆叠的效果
        * 改变图片的left值来达到动画的效果
    * 点击 [demo](https://laginalin.github.io/jQuery-practice/carousel/手风琴效果.html) 查看效果
