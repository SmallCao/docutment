### windows新终端
![windows terminal](res/w_ter.png)

**可以自定义主题：**
1. 打开设置
![](res/setting.png)
2. 选择主题
https://atomcorp.github.io/themes/

![选择主题](res/theme_site.png)

将选择好的主题配置信息，放在下图`schemes`集合里

![修改配置文件](res/config_modify.png)

修改上图`list`增加`colorScheme` 名字对应添加的schemes中的`name`

### 不够炫酷？修改背景图片，
```json
"backgroundImage": "E:\\bg.png",
"backgroundImageOpacity": 0.3,
# 有四个选项 uniformToFill | none | fill | uniform
"backgroundImageStretchMode":"none",
```
![背景图设置](res/set_bg_image.png)
`注意图片路径的反斜杠-转义或者用正斜杠`：'/' 否则会设置失败

### 最终效果：
![效果图](res/design.png)
重新打开终端，ok