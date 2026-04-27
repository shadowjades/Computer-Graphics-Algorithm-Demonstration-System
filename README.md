# 计算机图形学算法演示系统 | Computer Graphics Algorithm Demonstration System

本软件是一个面向教学和研究的图形学算法集成演示平台。基于 Python 和 PyQt5 开发，集成了二维/三维图形的基本图元光栅化（直线、圆、三角形）、二维/三维几何变换（平移、旋转、缩放、对称、错切）、复合变换、直线裁剪（Cohen-Sutherland、Liang-Yuan）、三维模型读取与显示（STL/OBJ）、观察变换、投影变换（正投影、一点/两点/三点透视）、隐藏面消除（背面剔除法、Z-Buffer）、光照模型（均匀着色、Gaussian 平滑、Phong 着色）、纹理映射、光线追踪、阴影生成等核心算法。

软件界面友好，通过按钮即可快速查看各算法的可视化结果，适合计算机图形学课程的辅助教学和学生自学。

This software is an integrated demonstration platform for graphics algorithms, oriented to education and research. It is developed with Python and PyQt5, incorporating core algorithms such as:  
- 2D/3D primitive rasterization (lines, circles, triangles)  
- 2D/3D geometric transformations (translation, rotation, scaling, reflection, shearing)  
- Composite transformations  
- Line clipping (Cohen‑Sutherland, Liang‑Barsky)  
- 3D model loading and display (STL / OBJ)  
- Viewing transformation  
- Projection transformations (orthographic, one‑point / two‑point / three‑point perspective)  
- Hidden surface removal (back‑face culling, Z‑buffer)  
- Illumination models (uniform shading, Gouraud smoothing, Phong shading)  
- Texture mapping  
- Ray tracing  
- Shadow generation  

The software provides a user‑friendly interface: each algorithm can be visualized by clicking a corresponding button. It is well suited for assisting teaching and self‑learning in computer graphics courses.

**版本 | Version**：V1.0  
**开发语言 | Development language**：Python 3.8+  
**主要依赖 | Main dependencies**：PyQt5, NumPy, Matplotlib, Pygame, VTK, scikit‑image  
**可执行文件 | Executable**：Packaged as a single Windows `.exe` file, requiring no Python environment to run.
