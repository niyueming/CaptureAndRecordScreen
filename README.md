# CaptureAndRecordScreen
实现Android5.0以上系统的录屏与截屏
[博客讲解](http://blog.csdn.net/leif_/article/details/50971659)

防止被录屏
=====
```
getWindow().addFlags(WindowManager.LayoutParams.FLAG_SECURE);
```
