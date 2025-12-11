# QtWebEngine-with-mp4-support
支持MP4视频解码的QtWebEngine二进制文件.  
直接替换QtWebEngine二进制文件即可使用.  
## 修改内容
1.设置`webengine_proprietary_codecs = ON`以启用MP4解码.  
2.解除chromium离屏渲染的60帧限制, 自动匹配Windows屏幕刷新率.
