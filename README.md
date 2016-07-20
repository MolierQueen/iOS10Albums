#iOS10中相册的一些变化
* 整体UI变化
![相册](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/IMG_0068.PNG?raw=true)

* 新加入回忆功能，该功能是将你之前一段时间所创建的照片自动放到回忆中，当然你也可以自己手动将照片放入回忆中。点击后用户可以在地图中看到你照片的生成地点，同时系统会根据你的头像与相关的地点联系在一起，在视频方面，新的照片系统也可以将你的情绪与音乐放在一起，让你更方便回忆，简单来说，就是更利于用户记忆，另外也让用户更有参与感。

* 新增LivePhoto编辑功能。

* 增加了人脸识别的功能，可根据面孔将照片进行分类(同一个人的照片或者照片中有这个人的话那就是一类)。不过目前的iOS10测试版发现在一次性导入大量图片的时候他需要进行任务查找分类，这个过程还是比较漫长的。不过准确率还是不错的，如果系统有某些照片没有识别出来的话，还支持用户向某个分类中添加人物照片。

* iOS10相册还具有标记功能，针对iPad、iPhone有不同的操作方式，用户可放大图片，并在图片上进行涂鸦或添加文字内容XXXXXXX。

* 将照片以视频的方式查看，同时支持编辑该视频，包括视频字幕、背景音乐、片长、还可对视频中的照片进行增删操作，但是编辑该视频的前提是需要将该视频先手动加入回忆分类中。

* 在iOS10中使用photos.framework时候需要在plist中加入提示，不然获取不到使用相册的权限，类似于iOS8中获取地理位置的变化。
