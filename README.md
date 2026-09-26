# EasyGL-EasyX_features_on_OpenGL
EasyX features on OpenGL


**easygl.h**

用 OpenGL 实现的 EasyX 兼容绘图库，纯头文件，C11 / C++ 通用。

照着 EasyX 的文档写代码就能跑：initgraph、circle、putimage、
outtextxy 这些名字和参数都保持原样。图形经 GPU 加速，额外支持
半透明、渐变、图像混合和后处理着色器。

用法：把 easygl.h 复制到工程目录，只在一个 .c / .cpp 文件里
include 它，编译时链接 opengl32、gdi32、user32。

    gcc -std=c11 main.c -o app.exe -lopengl32 -lgdi32 -luser32

运行环境：Windows XP(sp3) 及以上，OpenGL 3.0 及以上。


**easygl帮助文档.hta**

帮助文档，双击打开，不需要安装也不联网。

256 页，13 个分类，完整覆盖库内所有函数。顶部三个标签：
目录（可折叠的分类树）、索引（按字母排序）、搜索（支持中文）。

另有「关于 OpenGL」「兼容性」「示例程序」三章，其中示例程序
是 11 个完整可编译的例子，可直接复制进工程运行。


**作者**


TWXH

版本 20260926
