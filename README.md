# CommemorativeBook

# 纪念册，同学、亲友、朋友等综合纪念册。包含照片的分享，QQ分享、空间分享、微信分享、朋友圈分享、蓝牙分享等等。


# 设计需求

1、打开APP，有开场图片，点击图片有链接，倒计时n（s），时间过后进入页面2。
 
2、页面上面搜索条，可以搜索任何班级的任何人，下面的各个班级（N个班，手指滑动往下翻）的方块链接，点击班级方块链接，进入页面3.
 
3、点开班级，里面有该班级各个同学的方块链接，名字按首字母排列，方块是个人照片下方有姓名，点击图片方块进入该同学个人相册。
 
4、个人相册首先显示的是他的全部照片，类似缩略图，可以点击个人照，集体照等选项细分出其中对应的部分照片，只显示这部分照片，再点击全部才全部显示，照片可以单个或多个选中（照片下有小圆圈可以选中）进行分享（可以分享到微信和QQ）和下载，单击一张照片可以全屏显示，左右滑动是上一张下一张观看
 
5、回到主页面，搜索个人照片，搜索完成显示如图，一个显示一个，有同名的并排显示，点击图片进入个人相册。
 
6、回到个人相册，点击联系作者，进入一个页面。这个页面可以我自己编辑文字图片。



# 照片上传

1、在任意一台电脑上，打开浏览器，输入如下地址：http://114.116.94.16:8080/SpecialDeviceExam/static/admin.jsp

2、上传事项，首先要输入学生的学号，即前面录入的学生编号；再次，需注意的是 如果第一次给学生上传照片，应该首先上传一张 照片类型 为 “头像”的照片，后面再上传其他类型的照片；最后点击“上传” 完成图片的上传。
 
3、等待上传完成，即可在“蟋蟀相册”app中查看相关的照片了。

# 注意事项

由于服务器配置等原因，以及没有采用分布式服务、缓存服务器，上传照片时，请尽量一次性低于100张，最好50张以内，效果最好。因为服务器很难处理高并发。

