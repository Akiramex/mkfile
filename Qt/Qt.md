## Qt Json

https://blog.csdn.net/rong11417/article/details/104252927

[Qt 操作Json格式文件（创建、插入、解析、修改、删除）](https://blog.csdn.net/cpp_learner/article/details/118421096)

## Qt Http

https://www.cnblogs.com/ybqjymy/p/15791035.html



## Qt qApp

在Qt中，`qApp`是一个全局指针，它指向当前的`QApplication`或`QGuiApplication`对象。

[](https://blog.csdn.net/qq_21438461/article/details/131830930)



## Qt延迟

[](https://liucjy.blog.csdn.net/article/details/132916934)



## Qt尺寸

[](https://zhuanlan.zhihu.com/p/28972208)



## Qt切换页面

Widget[](https://blog.csdn.net/xiaopei_yan/article/details/106693065)



## Qt类

### QUrl

[](https://blog.csdn.net/u012260238/article/details/53944984)

### QMediaPlayer

[](https://blog.csdn.net/zhaoyun_zzz/article/details/90290552)



### QProcess

~~~c++
    QObject *parent;
    ...
    QString program = "./path/to/Qt/examples/widgets/analogclock";
    QStringList arguments;
    arguments << "-style" << "fusion";

    QProcess *myProcess = new QProcess(parent);
    myProcess->start(program, arguments);
~~~

QProcess then enters the [Starting](https://doc.qt.io/qt-5/qprocess.html#ProcessState-enum) state, and when the program has started, QProcess enters the [Running](https://doc.qt.io/qt-5/qprocess.html#ProcessState-enum) state and emits [started](https://doc.qt.io/qt-5/qprocess.html#started)().

[](https://blog.csdn.net/lizhong2008/article/details/136840521)

[](http://qt5.digitser.top/5.15/zh-CN/qprocess.html)
