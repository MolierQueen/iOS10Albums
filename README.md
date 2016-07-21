#iOS10中相册的一些变化
* 整体UI变化


![相册](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/%E6%95%B4%E4%BD%93UI%E5%9B%BE.PNG?raw=true)

* 新加入回忆功能，该功能是将你之前一段时间所创建的照片自动放到回忆中，当然你也可以自己手动将照片放入回忆中。点击后用户可以在地图中看到你照片的生成地点，同时系统会根据你的头像与相关的地点联系在一起，在视频方面，新的照片系统也可以将你的情绪与音乐放在一起，让你更方便回忆，简单来说，就是更利于用户记忆，另外也让用户更有参与感。

![回忆相册](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/1F659074-5965-4BB4-BBB0-BC3F71ADC2A5.png?raw=true)
![回忆相册](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/5099A0D5-C491-43C3-BBE5-8DBD9D6AA973.png?raw=true)



* 新增LivePhoto编辑功能。

* 增加了人脸识别的功能，可根据面孔将照片进行分类(同一个人的照片或者照片中有这个人的话那就是一类)。不过目前的iOS10测试版发现在一次性导入大量图片的时候他需要进行任务查找分类，这个过程还是比较漫长的。不过准确率还是不错的，如果系统有某些照片没有识别出来的话，还支持用户向某个分类中添加人物照片。

![人物](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/%E4%BA%BA%E7%89%A9cell.png?raw=true)
![人物](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/%E6%AD%A3%E5%9C%A8%E6%9F%A5%E6%89%BE%E4%BA%BA%E7%89%A9.png?raw=true)
![人物](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/%E6%89%8B%E5%8A%A8%E6%B7%BB%E5%8A%A0%E4%BA%BA%E7%89%A9.png?raw=true)

* iOS10相册还具有标记功能，针对iPad、iPhone有不同的操作方式，用户可放大图片，并在图片上进行涂鸦或添加文字内容。

![标记](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/A5E7BC39-F1B6-4134-9AD8-CACBF9735CAA.png?raw=true)
![标记](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/7C7CFA3D-722E-4CCE-9320-E1E02D145387.png?raw=true)

* 将照片以视频的方式查看，同时支持编辑该视频，包括视频字幕、背景音乐、片长、还可对视频中的照片进行增删操作，但是编辑该视频的前提是需要将该视频先手动加入回忆分类中。

![视屏预览](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/092DFF4F-B208-4C22-9E36-B67E7465232D.png?raw=true)
![视屏预览](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/D2B5FA59-996C-4B53-87EB-43A08EC2863B.png?raw=true)
![视频预览](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/25191DC6-824D-4975-A767-DFC23183387B.png?raw=true)
![视频预览](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/EF69C022-05F6-4FE2-AAE1-82EFA0E3FD19.png?raw=true)
![编辑视频](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/7878B738-665F-44FB-9899-23A4FF85C882.png?raw=true)


* 在iOS10中使用photos.framework时候需要在plist中加入提示，不然获取不到使用相册的权限，类似于iOS8中获取地理位置的变化。

![iOS10问题](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/194BFDCE-E46D-463A-BD0B-A273138D9AE5.png?raw=true)
![iOS10问题](https://github.com/zhangninghao/iOS10Albums/blob/master/Resource/Pasted%20Graphic%201.png?raw=true)


