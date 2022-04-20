English | [简体中文](README_ZH.md)

# ym Context Menu Helper

## Introduction
Usually we write small programs to help us with things, but we have to start them via termimal, cmd or ide each time, which is very cumbersome.<br>
This project will help you to extend your context menu more easily.

I.e.: make your own customized features to add to the menu.

I will occasionally update some generic scripts to this repo, to help people without programming experience, users can download configuration files to use it.

Currently the whole project ~80% is based on Python3, and the rest is cpp or c# ,made by modifying the registry, but there will be some limitations for the operation of multiple files and folders.<br>
I will try to refactor these features soon and will upload them officially then.
For now, it's just to set a goal to keep myself motivated.

XD

## Examples
> Only ~10% of the more common functions are shown here, while the rest are lesss used,or biased towards my personal customization, such as the "Merge Texture Channels" in the picture below. It will merging multiple textures into 1 RGBA texture

<img src="https://youngmoe.com/pic/Snipaste_2022-04-20_14-38-37.png" width = 750px />
<img src="https://youngmoe.com/pic/Snipaste_2022-04-20_14-37-44.png" width = 750px />

> Works on folders, will process all files in the folder according to the file name rules

<img src="https://youngmoe.com/pic/Snipaste_2022-04-20_14-39-14.png" width = 750px />


## Open source libraries used

### ffmpeg
- [FFmpeg/FFmpeg](https://github.com/FFmpeg/FFmpeg)
### pillow
- [python-pillow/Pillow](https://github.com/python-pillow/Pillow)


## License
[GNU GPLv3](https://github.com/ShiinaRinne/ymContextMenuHelper/blob/master/LICENSE)