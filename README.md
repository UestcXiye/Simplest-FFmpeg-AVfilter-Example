# Simplest FFmpeg AVfilter Example
 最简单的基于 FFmpeg 的 AVfilter 例子（水印叠加）。该例子完成了一个水印叠加的功能。可以将一张透明背景的 png 图片（my_logo.png）作为水印叠加到一个视频文件上。需要注意的是，其叠加工作是在解码后的 YUV 像素数据的基础上完成的。   程序支持使用 SDL1.2 显示叠加后的 YUV 数据，也可以将叠加后的 YUV 输出成文件。
