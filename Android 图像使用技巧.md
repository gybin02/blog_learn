## Android 图像使用技巧
https://blog.csdn.net/bedisdover/article/details/73189053

1. 使用自带的Materail 图标库：

Android Studio 为我们提供了更方便的方式，操作流程如下：
1. 在 res文件夹右键，选择 New –> Vector Asset
2. 确定文件名、图标、大小、透明度等
3. 个性化定制
可以通过修改生成的xml文件来实现图标的定制，修改 android:fillColor 以改变图标颜色，修改 android:viewportWidth 和 android:viewportHeight 以修改图标大小

保存会会在 drawable文件夹下生成 drawable.xml文件，可以在任意地方使用这些 矢量资源


## 生成launcher图标等；
 在 res文件夹右键，选择 New –> Image Asset，选中资源后可以生成多个样式PNG图片


## 更多来源
Material icons 官网中提供的图标样式有限，要想轻松使用更多的图标，可以从其它图标网站下载图标，然后转换为 Material icons
1. 下载 SVG 格式图标
2. New –> Vector Asset –> Local file
3. 同上

常用图标网站：

阿里巴巴矢量图标库

The Largest Icon Pack EverThe Largest Icon Pack Ever

Fontello


### 常用图标库

1. Material icons  
2. https://fontawesome.com/
3. 

### 常用字体库 依赖

Android-Iconics ：https://github.com/mikepenz/Android-Iconics
