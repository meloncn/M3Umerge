# M3U Merge Tool

------

用于快速将同文件夹下N个 .m3u 播放源列表文件进行合并。生成一个可以播放的播放源集合。

> * Python > 3.6


## 使用说明：

将你的N个.m3u列表文件放置在与脚本相同目录下，运行本脚本

    python3 M3Umerge.py

运行过后同级目录产生新文件：mergeFile.m3u
    
---


## 特别说明

脚本不会修改原有行属性等信息，避免不同平台终端出现问题。
脚本没有去除重复的功能。
当.m3u文件格式有误时脚本抛出错误停止运行。该问题不是BUG而是特性。

---