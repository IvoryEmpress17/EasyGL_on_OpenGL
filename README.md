# EasyGL_on_OpenGL
EasyX features on OpenGL

这是第三方兼容实现、与 EasyX 官方无关，也和 Github 上别的同名项目无关。

作者水平不好...

因学业原因，代码由 AI 代笔，为了解决雷霆编码问题把注释全搞成英文了。

基本没bug了。

最好在MinGW GCC上跑，别的我不确定跑不跑得了，理论上可以(C11)。

**easygl.h**

用 OpenGL 实现的 EasyX 兼容绘图库，纯头文件，C11 / C++ 通用。

initgraph、circle、putimage、outtextxy 这些名字和参数都保持原样。图形经 GPU 加速，额外支持半透明、渐变、图像混合和后处理着色器。

用法：把 easygl.h 复制到工程目录，只在一个 .c / .cpp 文件里
include 它，编译时链接 opengl32、gdi32、user32。

	-std=c11/-std=c++11

    -lopengl32 -lgdi32 -luser32

运行环境：Windows XP(sp3)(也许) 及以上，OpenGL 3.0 及以上。


**easygl帮助文档.hta**（改成html就是网页了）

帮助文档，Windows 双击打开。


**作者**


TWXH
这个IvoryEmpress17是我的github账号

邮箱：3574403974@qq.com

版本 20260927
