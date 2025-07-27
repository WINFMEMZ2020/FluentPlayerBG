# FluentPlayerBG
Generate fluent, aesthetic backgrounds from album covers — lightweight, cacheable, and perfect for wearables and music apps.<br>
以低性能创建适用于音乐播放器的背景图像，具有轻量，可缓存的特点。可适用于可穿戴设备或者其它音乐app。

# How to use 【使用方法】
1.Use pip to install the required dependencies.<br>
使用pip安装所需要的依赖
```powershell
pip install mutagen opencv-python pillow numpy
```

2.Enter the path of the mp3 or flac file. Be sure to use an absolute path.<br>
输入mp3或者flac文件的路径,注意使用绝对路径。
```powershell
PS D:\> python .\main.py
请输入mp3文件或flac文件路径：D:\test.mp3
```

3.The final background image `merged_image.jpg` will be created in the same folder as the Python script, while the extracted album cover will be saved alongside the original music file.<br>
将会在与py脚本同目录下生成最终的结果`merged_image.jpg`，同时在音乐文件同目录生成提取后的专辑封面文件。

# Usage Notes
1.This is a demonstration program that only showcases the core processing logic. You need to handle exceptions and edge cases yourself.<br>
这只是个演示程序，只展示处理的逻辑。需要自行处理异常情况。<br>
2.Please comply with the open source license terms.<br>
请遵守开放源代码使用协议。

# DEMO
