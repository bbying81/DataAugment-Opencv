# DataAugment-Opencv
Combine image crop,color shift,rotation and perspective transform together to complete a data augmentation script.
## 引言
数据增广主要包括：水平/垂直翻转，旋转，缩放，裁剪，剪切，平移，对比度，色彩抖动，噪声等
## 安装要求
- linux
- anaconda
- opencv-3.1.0
- python3.6
## 环境安装
在anaconda中新建一个opencv36环境（python3.6)。

  - windows系统：直接在anaconda新建的环境中选择opencv安装即可
  
  - linux系统：在终端进入到opencv36环境中
(opencv36) bbying@bbying-Vostro:~/anaconda3/envs/opencv36$ conda install -c menpo opencv3
即可完成opencv安装

  - 注意事项：
  - 1.选择puthon3.6是因为在最初python3.5下出现了以下错误
  UnsatisfiableError: The following specifications were found to be incompatible with each other:
  -pip -> python[version='>=3.6,<3.7.0a0']
  
  - 2.之所以linux用上述方法安装opencv是因为直接像window那样安装后，在执行cv操作时，遇见了
  error: -------src-dir-------/opencv-2.4.10/modules/highgui/src/window.cpp:501: error: (-2) The function is not implemented. Rebuild the library with Windows, GTK+ 2.x or Carbon support.  If you are on Ubuntu or Debian, install libgtk2.0-dev and pkg-config, then re-run cmake or configure script in function cvShowImage.
  
  - 3.不要直接conda install opencv3,一定要像上面的命令那样写
  
  ## 数据集
  - 从LFW Face Database 中挑了16张图片
  http://vis-www.cs.umass.edu/lfw/
  
  
  ## 参考
  https://zhuanlan.zhihu.com/p/43665254
  
  
  
  

