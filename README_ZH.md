# ym Context Menu Helper

## 简介
通常我们会编写小程序来帮助自己处理一些事情，但每次都得通过termimal、cmd或者ide启动，这样非常麻烦。<br>
此项目可以帮助你更轻松的来扩展自己的右键菜单

例如：制作自己的定制化功能添加到菜单中

我会偶尔更新一些自己觉得比较实用的通用型脚本到这个Repo，来帮助没有编程经验的人，用户可自行下载配置文件

目前整个项目~80%基于Python3，其余为cpp或c#，通过修改注册表制作，但对于多文件与文件夹的操作会受到一些限制。<br>
过段时间会尝试重构这些功能，届时会正式上传，目前仅当作立个目标，让自己不摸鱼xd


## 示例
> 这里展示的只有~10%左右的较为常用功能，其余应用场景较少，或偏向我个人的定制化，例如下图中的Merge Texture Channels：将多张纹理合并到一张RGBA格式的的纹理中

<img src="https://youngmoe.com/pic/Snipaste_2022-04-20_14-38-37.png" width = 750px />
<img src="https://youngmoe.com/pic/Snipaste_2022-04-20_14-37-44.png" width = 750px />


> 作用于文件夹，将根据文件名规则，对文件夹内的所有文件进行处理
  
<img src="https://youngmoe.com/pic/Snipaste_2022-04-20_14-39-14.png" width = 750px />


## 使用的开源项目

### ffmpeg
- [FFmpeg/FFmpeg](https://github.com/FFmpeg/FFmpeg)
### pillow
- [python-pillow/Pillow](https://github.com/python-pillow/Pillow)


## License
[GNU GPLv3](https://github.com/ShiinaRinne/ymContextMenuHelper/blob/master/LICENSE)