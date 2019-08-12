# KeyboardTest
Keyboard test applet
This is a modify version of origin application.
This version has following features:
(英语不好，直接写中文了）
较为完整的配置文件导入导出系统
根据指定参数批量绘制矩形（长，宽，距离）


这个版本不是很完善，但是可以作为参考。比如，把程序稍微改造一下，让他导入生成的json，按照布局来创建button之类的。
另外，键盘上按键的id是有顺序的，比如1-9是连着的，abcd-xyz也是连着的。这就是这个版本的目的，利用顺序来批量生成id与按钮（应当被放在的）位置的对应表（json格式，程序已加入json支持）。
