 # art
音视图的制作

## 视频的分割

* ffmpeg -i input.avi -vcodec copy -acodec copy -ss 00:00:00 -t 00:30:00 output1.avi
* ffmpeg -ss 0 -t 100 -i source.m4v -vcodec copy -acodec copy part1.m4v
* avconv -i input.avi -vcodec copy -acodec copy -ss 00:00:00 -t 00:30:00 output1.avi
* avconv -ss 0 -i source.m4v -t 100 -vcodec copy -acodec copy part1.m4v



参考

* [分割](http://askubuntu.com/questions/56022/what-to-use-to-quickly-cut-audio-video)
* [合并](https://trac.ffmpeg.org/wiki/Concatenate)
* [缩放](https://trac.ffmpeg.org/wiki/Scaling%20(resizing)%20with%20ffmpeg)


## 图像处理
[命令行缩放,转换和修改图像](https://www.howtogeek.com/109369/how-to-quickly-resize-convert-modify-images-from-the-linux-terminal/)
[ImageMagick-图像魔术命令行](https://www.imagemagick.org/script/command-line-processing.php)
