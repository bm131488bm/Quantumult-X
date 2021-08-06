Quantumult X使用方法：
1、订阅图标
打开QuanX 配置文件-编辑，找到［server_remote］字段，在想要增加图标的相应订阅中修改，在enable＝true之前加上 img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Alpha/name.png 注意此句和前后句都要用英文逗号隔开，并且逗号后先要空一格

完整示例：https://raw.githubusercontent.com/crossutility/Quantumult-X/master/server-complete.txt, tag=Sample-02, as-policy=static, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Alpha/name.png, enabled=false

2、策略图标
2.1 UI中使用

长按想要更改图标的策略组，弹出菜单选择编辑，在图标一栏填写

**https://raw.githubusercontent.com/Orz-3/mini/master/Color/name.png

2.2 文本编辑：

打开QuanX 配置文件-编辑，找到［policy］字段，在想要增加图标的相应策略段落中修改，在enable＝true之前加上 **img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/name.png 注意此句和前后句都要用英文逗号隔开，并且逗号后先要空一格

完整示例：static=policy-name-1, Sample-A, Sample-B, Sample-C, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/name.png

Loon使用方法：
1 UI中使用

点击下方“策略”选项卡，在策略界面点长按想要更改图标的订阅/策略组，弹出界面中，在图标一栏填写

**https://raw.githubusercontent.com/Orz-3/mini/master/Color/name.png

2 文本编辑： 打开Loon配置选项卡，点击编辑-文本编辑，找到[Remote Proxy]/［Proxy Group］字段，在想要增加图标的相应订阅/策略段落中修改，加上 **img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/name.png 注意此句和前句要用英文逗号隔开

注：请将使用方法中的name.png替换成相应文件的文件名
