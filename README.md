# DirectX12CodeSamples

2019.04.24更新： 
12.4 间接渲染	361 
12.4.1	间接渲染的简介	361 
12.4.2	间接渲染函数	362 
12.4.3	间接命令和命令签名对象	363 
12.4.4	字节对齐方式	368 
12.5 计算着色器	369 
12.5.1	计算着色器的简介	369 
12.5.2	线程组和线程	370 
12.5.3	计算着色器代码	373 
12.5.4	通用计算根签名	375 
12.5.5	通用计算管线状态	378 
12.5.6	通用计算的运行	382 


2019.03.25更新：  
DirectX12 3D游戏开发	2  
致谢	3  
第一部分 DirectX11入门	15  
第一章 DirectX的邂逅	15  
1.1 DirectX简介	15  
1.1.1	DirectX是何物	15  
1.1.2	DirectX的各个版本	15  
1.1.3	DirectX和OpenGL	16  
1.1.4	DirectX、OpenGL该学哪一个	17  
1.2 DirectX的组件	17  
1.2.1	DirectX的组件	17  
1.2.2	DirectX逝去的组件	18  
1.3 DirectX渲染管线基本概念	19  
1.3.1	DirectX的固定渲染管线	19  
1.3.2	DirectX的可编程渲染管线和着色器语言	20  
1.3.3	DirectX新增的着色器	21  
1.4 本章小结与练习	24  
1.4.1	小结	24  
1.4.2	习题	24  
第二章 3D基础数学原理	26  
2.1 坐标系	26  
2.1.1	2D坐标系	26  
2.1.2	3D坐标系	27  
2.1.3	其他坐标系	28  
2.2	向量	29  
2.2.1 向量的概念	29  
2.2.2 向量长度和归一化	30  
2.2.3 向量的相加与相减	31  
2.2.4 向量和标量的乘法	32

2.2.5 向量的点积	32 

2.2.5 向量的叉积	33 

2.2.6 位置和位移向量	33 

2.3 矩阵	34 

2.3.1	矩阵的定义	34 

2.3.2	矩阵的加减法	34 

2.3.3	矩阵的乘法	35 

2.3.4	单位矩阵	36 

2.3.5	转置矩阵	36 

2.4 欧拉角	36 

2.4.1	欧拉角的定义	36 

2.5 四元素	37 

2.5.1	四元素	37 

2.6 本章小结与练习	38 

2.6.1	小结	38 

2.6.2	习题	38 

第三章 Directx3D入门程序	39 

3.1 第一个Directx3D程序	39 

3.1.1	创建一个空项目	39 

3.1.2	添加代码	43 

3.1.3	代码分析	49 

3.1.4	代码编译	52 

3.2 渲染一个三角形	56 

3.2.1	顶点	56 

3.2.2	顶点缓存（Vertex Buffer）	57 

3.2.3	加载Shader文件	59 

3.2.4	输入布局（Input Layout）	60 

3.2.5	图元	62 

3.2.6	渲染三角形	62 

3.2.7	释放资源	64 

3.3 渲染旋转的立方体	64 

3.3.1	颜色	64 

3.3.2	索引缓存（Index Buffer）	65 

3.3.3	常量缓存(Constant Buffer)	67 

3.3.4	空间变换	68 

3.3.5	渲染立方体	70 

3.4 本章小结与练习	72 

3.4.1	小结	72 

3.4.2	习题	72 

第四章 HLSL入门	73 

4.1 HLSL基本语句	73 
4.1.1	HLSL简述	73 
4.1.2	基本数据类型Data Types	73 
4.1.3	控制语句Flow Control	75 
4.1.4	语义Semantics	76 
4.1.5	寄存器register	77 
4.1.6	着色器型号Shader Models	78 
4.2	编写HLSL代码	78 
4.2.1	全局变量	78 
4.2.2	输入输出结构	79 
4.2.3	入口函数	79 
4.2.4	内置函数	80 
4.2.5	顶点着色代码	81 
4.2.6	像素着色代码	81 
4.2.7	编译HLSL代码	81 
4.3	纹理映射	83 
4.3.1	贴图、纹理、DDS格式图片	83 
4.3.2	制作DDS格式图片	83 
4.3.3	纹理的UV坐标	84 
4.3.4	纹理过滤（Texture Filtering）	86 
4.3.5	纹理的寻址方式	87 
4.4 渲染带纹理的立方体	89 
4.4.1	着色器资源视图	89 
4.4.2	纹理采样状态	90 
4.4.3	纹理渲染	91
4.4.4	带纹理的HLSL代码	93
4.5 效果框架Effect11	94
4.5.1	Effect11简述	94
4.5.2	Effect11对象创建	94
4.5.3	Effect11的HLSL代码规范	97
4.5.4	Effect11接口和数据结构	99
4.5.5	Effect11的输入布局	100
4.5.6	Effect11的渲染	101
4.6 本章小结与练习	103
4.6.1	小结	103
4.6.2	习题	103
