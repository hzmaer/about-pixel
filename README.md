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
