
# pcr-record

本项目为[HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot/) 的公主连结人物语音插件。

## 使用方法

**[语音+角色名]** 或 **[角色名+语音]**

随机播放一段指定人物的语音,人物名可以为HoshinoBot能够识别的各种外号,例如:语音ue

## 安装方法

1. 在 `hoshino/modules` 目录下 `git clone https://github.com/zyujs/pcr-record`
1. 在hoshino资源目录 `res` 下创建 `record` 目录放置人物语音,语音资源需要寻找资源包或自行收集. 人物语音文件的目录形式为 `res/record/[四位数字的人物ID]/*.silk`
1. 在__bot__.py中添加 `pcr-record` 使能项
