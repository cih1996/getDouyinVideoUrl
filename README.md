# getDouyinVideoUrl
批量获取个人主页上的抖音作品mp4视频文件下载地址


通过Chrome浏览器自带的开发者工具，在console视图下注入js代码实现批量获取抖音原视频MP4下载链接

实现原理：

1、使用classname获取到所有作品元素，并获取点赞数量进行筛选过滤

2、由于当前页面不直接包含mp4链接，通过创建一个frame框架元素后，逐一自动打开视频页面来获取mp4视频地址


使用方法：

呼出console控制台

将down.js直接复制即可全自动获取

获取完成后会自动输出所有mp4链接

您可以通过迅雷或python等方式批量下载到本地。


演示地址：

https://www.youtube.com/watch?v=sE1aab7t9rw
