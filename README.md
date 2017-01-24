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
