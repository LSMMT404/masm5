
## 第十五章

键盘输入时的中断过程。

![keyboard_int9](https://github.com/jungle85gopy/masm5/blob/master/chap15/keyboard_in.png)

### 15.4 显示a-z，ESC改变颜色

注意调整延迟的时长，以及从键盘读入的是扫描码。


### 15.5 F1改变全屏显示颜色
略。


### 实验15 输入并松开a时全屏输出A
注意，此程序执行后即退出，当有键盘输入时，int9中断被调用，如果输入为a，并且松开时，则全屏输出。





