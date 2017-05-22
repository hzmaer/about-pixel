# about-pixel
屏幕尺寸，屏幕像素密度，devicePixelRatio，viewport

1.什么是屏幕尺寸？

屏幕尺寸：屏幕可视区对角线的长度。

2.什么是屏幕像素密度？

3.什么是devicePixelRatio？什么是设备物理像素？什么是设备独立像素？设备独立像素与屏幕像素密度有什么关系？

设备物理像素就是物理像素，设备独立像素也是css像素，也是逻辑像素

![Alt text](https://github.com/hzmaer/about-pixel/blob/master/images/%E5%B1%8F%E5%B9%95%EF%BC%8C%E5%83%8F%E7%B4%A0%E5%AF%86%E5%BA%A6%EF%BC%8C%E8%AE%BE%E5%A4%87%E5%83%8F%E7%B4%A0%E6%AF%94.jpg)

举例说明，比如iphone6s,其横向物理像素为750px,横向设备独立像素为375px,将其带入上面的公式，可以得到其devicePixelRatio=2;
         再比如iphone6s plus，其横向物理像素为1080px,横向设备独立像素为414px,将其带入上面的公式，可以得到其devicePixelRatio大约为2.6;
         
4.viewport是什么意思？

<meta name="viewport" content="width=device-width,initial-scale=1.0  maximum-scale=1.0 user-scalable=0">

在苹果的规范中，meta viewport 有6个属性(暂且把content中的那些东西称为一个个属性和值)，如下：

1.width:设置layout viewport的宽度，为一个正整数，或字符串"device-width";

2.initial-scale:设置页面的初始缩放值，为一个数字，可以带小数;

3.maximum-scale:允许用户的最大缩放值，为一个数字，可以带小数;

4.minimum-scale:允许用户的最小缩放值，为一个数字，可以带小数;

5.user-scalable:是否允许用户进行缩放，值为"no"或"yes", no 代表不允许，yes代表允许;

6.height:设置layout viewport  的高度，这个属性对我们并不重要，很少使用;




