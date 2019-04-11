# SecretWatermark
此项目是使用fftw实现的在图像频域添加明码水印,对图像本身影响不大，但遭受JPG压缩攻击可能使水印识别度降低，需调整适当参数，png和bmp格式识别效果较好

此项目支持windows、linux和mac平台

## 编译方法
使用XStudio打开SecretWatermark.xprj,F5即可

此项目依赖qt 和fftw包，如编译不能通过，打开[项目属性]将依赖库全部删除，然后用菜单[工具] -> [包管理]重新将包qt5.9.1和fftw添加到工程后再编译。

如果没有fftw包请到libraries去下载 fftw.xp 然后使用菜单[工具] -> [包管理]导入.

## 使用方法:

### 添加水印
1.点击打开/查看图片，选择要添加水印的图片。
2.点击添加水印，选择水印图片。
3.查看预览效果，并调整参数。
4.点击保存将添加好水印的图片存为文件。

### 查看水印
1.点击打开/查看图片，选择要查看水印的图片，即可在预览区域显示水印信息。

此项目可进行任意用途的二次开发和分发。

## windows 下运行图

![](https://github.com/ixlang/SecretWatermark/blob/master/preview.png)