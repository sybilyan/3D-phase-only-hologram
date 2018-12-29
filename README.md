# 3D-phase-only-hologram
For EE6618 the second assignment, including down sample and error diffusion

生成hologram的完整代码

用法：c源代码包括原图傅里叶及菲盘傅里叶过程，经过phase only（即UERD、BERD、down sample选其一），最后原图和菲盘 反傅立叶重建过程

使用UERD或BERD只需将文件中cghUERD.cpp或者cghBERD.cpp 的 UERD或BERD 部分删除即可
使用downsample只需将任意一cgh.cpp文件 downsample 函数释放，并删除error方法函数部分
即可得重建图

若使用激光束实现即将reconstruct函数注释掉 此时显示屏无法显示清晰图像
