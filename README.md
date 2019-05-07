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

第五章 界面	104

5.1 DXUT11的对话框	104

5.1.1	对话框资源管理器	104

5.1.2	对话框及其控件	106

5.1.3	滑动控件	108

5.1.4	单选框	109

5.1.5	复选框	111

5.1.6	下拉框	112

5.2 Win32应用程序	114

5.2.1	什么是Win32	114

5.2.2	创建Win32窗口的代码	114

5.2.3 注册窗口	117

5.2.4 创建窗口	118

5.2.5 消息循环处理	119

5.2.6 消息回调函数	120

5.3 Direct3D初始化	120

5.3.1	设定Direct3D设备能力	120

5.3.2	设定数据交换链	122

5.3.3	创建设备和数据交换链	123

5.3.4	创建视口和得到DXGI	126

5.3.5	渲染目标和渲染目标视图	128

5.3.6	渲染、重组和释放	129

5.4 Direct2D初始化	132

5.4.1	创建Direct2D设备	132

5.4.2	创建Direct2D渲染目标位图	134

5.4.3	Direct2D渲染和重组	136

5.5 Direct2D界面元素	137

5.5.1	画刷的应用	137

5.5.2	渐变画刷设定	140

5.5.4	渐变画刷的创建	141

5.5.3	创建WIC对象	143

5.5.4	创建和绘制Direct2D位图	144

5.5.5	位图画刷	148

5.5.6	文本的渲染	149

5.6 本章小结与练习	152

5.5.1	小结	152

5.5.2	习题	152

第六章 相机和模型文件加载	154

6.1 虚拟相机	154

6.1.1	相机的介绍	154

6.1.2	透视相机的使用	155

6.1.3	正交相机格式	158

6.2 3D网格	160

6.2.1	3D网格介绍	160

6.2.2	sdkmesh格式转换	161

6.2.3	使用sdkmesh文件	162

6.3 本章小结与练习	165

6.3.1	小结	165

6.3.2	习题	165

第七章 光照	166

7.1 光	166

7.1.1	法线	166

7.1.2	光源	166

7.1.3	光反射	167

7.2 光照示例	169

7.2.1	环境反射示例	169

7.2.2	漫反射示例	170

7.2.3	镜面反射示例	174

7.2.4	点光源示例	178

7.3 本章小结与练习	184

7.3.1	小结	184

7.3.2	习题	184

第二部分 DirectX12 UWP入门	185

第八章 DirectX12 UWP框架	185

8.1 UWP窗口创建	185

8.1.1	UWP和Win32的区别	185

8.1.2	DirectX12 UWP模版	186

8.1.3	UWP入口函数	187

8.1.4	创建和初始化视图	188

8.1.5	绑定窗口的事件	190

8.1.6	资源加载卸载和运行	191

8.2 UWP事件处理函数	194

8.2.1	生命周期事件	194

8.2.2	窗口事件	195

8.2.3	显示信息事件	196

8.3 DirectX12设备资源创建	197

8.3.1	DirectX12运行步骤类	197

8.3.2	DirectX12设备资源类	198

8.3.3	DirectX12设备创建	199

8.3.4	DirectX12命令队列/列表和围栏的创建	201

8.4 DirectX12视图资源创建	203

8.4.1	DirectX12数据交换链	203

8.4.2	DirectX12渲染目标视图	206

8.4.3	描述堆属性	208

8.4.4	DirectX12深度模板视图	208

8.5 DirectX12根签名	212

8.5.1	应用数据存储ApplicationData	212

8.5.2	根参数和描述符范围	214

8.5.3	根签名优化标识和根签名布局	216

8.5.4	创建根签名ID3D12RootSignature	218

8.6 DirectX12游戏资源创建	219

8.6.1	异步加载着色器	219

8.6.2	图像命令列表和管道状态	220

8.6.3	创建命令列表	223

8.6.4	创建顶点缓存视图和索引缓存视图	224

8.6.5	常量缓存视图	228

8.6.6	WaitForGpu	230

8.7 DirectX12游戏循环	231

8.7.1	游戏逻辑循环	231

8.7.2	游戏渲染循环	232

8.7.3	清除渲染目标视图和深度视图	234

8.7.4	渲染操作	235

8.8 UWP应用程序打包和离线安装	236

8.8.1	设置Win10开发人员模式	236

8.8.2	UWP应用程序打包	237

8.8.3	PC机离线安装UWP应用	240

8.9 本章小结与练习	241

8.9.1	小结	241

8.9.2	习题	242

第九章 DirectX12 UWP简单实例	243

9.1 UWP带纹理的立方体	243

9.1.1	构建立方体的顶点	243

9.1.2	DX12纹理采样器	245

9.1.3	带纹理的根签名和描述符堆	246

9.1.4	创建纹理的堆内存	247

9.1.5	将纹理资源上传到GPU	249

9.1.6	创建纹理的着色器资源视图（SRV）	250

9.1.7	将渲染的纹理绑定到渲染管线	252

9.2 UWP带光照的球体	252

9.2.1	创建一个球体	252

9.2.2	球的着色器代码	255

9.2.3	创建新的常量缓存	257

9.2.4	为球添加光照	259

9.3 多个物体的渲染	261

9.3.1	封装常量缓存视图的堆	261

9.2.2	渲染2个位置的球体	265

9.2.3	渲染2张不同的纹理	269

9.2.4	封装像素着色器的常量缓存	272

9.2.5	使用2个不同的渲染状态	274

9.4 本章小结与练习	279

9.4.1	DX12描述符的总结	279

第十章 XAML和DirectX12	281

10.1 创建XAML应用程序	282

10.1.1	XAML简述	282

10.1.2	创建xaml窗口	282

10.1.3	添加XAML控件	284

10.2 创建DirectX-XAML应用程序	288

10.2.1	DirectX12和XAML	288

10.2.2	创建DirectX12-XAML工程	289

10.2.3	适配DirectX12-XAML工程	291

10.3 有交互的DirectX-XAML应用程序	294

10.3.1	有交互的UI	294

10.3.2	响应鼠标	296

10.3.3	响应键盘	298

10.3.4	播放视频和声音	299

第十一章 常见的纹理渲染方式	301

11.1 Alpha blending	301

11.1.1	透明的概念	301

11.1.2	透明的运用	302

11.2 两层纹理渲染	305

11.2.1	两层纹理的概念	305

11.2.2	两层纹理的着色代码	306

11.2.3	两层纹理的c++代码	308

11.2.4	两层纹理的混合	309

11.3 环境映射	310

11.3.1	环境映射的原理和立方贴图纹理	310

11.3.2	立方贴图制作和DDS	311

11.3.3	加载DDS文件	314

11.3.4	立方体纹理渲染	315

11.3.5	反射环境映射	317

11.3.6	折射环境映射	318

11.3.7	菲涅尔效果的环境映射	319

11.4 凹凸纹理映射	321

11.4.1	凹凸纹理映射原理	321

11.4.2	凹凸纹理着色器代码	323

11.4.3	改良凹凸纹理着色	326

11.5 贴图置换	329

11.5.1	贴图置换和法线映射的区别	329

11.5.2	贴图置换着色器代码	329

11.6 本章小结与练习	332

11.6.1	小结	332

11.6.2	习题	332

第十二章 几何着色和曲面细分	333

12.1 几何着色器	333

12.1.1	几何着色器的作用	333

12.1.2	几何着色器的简单应用	334

12.1.3	三角面细分	336

12.1.4	模型分裂	339

12.2 曲面细分阶段	342

12.2.1	曲面细分的优点	342

12.2.2	外壳着色器（Hull Shader）	343

12.2.3	域着色器（Domain Shader）	347

12.2.4	C++代码部分的修改	349

12.3 Curved PN Triangles	352

12.3.1	Curved PN Triangles原理	352

12.3.2	修改外壳着色器和域着色器代码	355

12.4 本章小结与练习	361

12.6.1	小结	361

12.6.2	习题	361

第十二章 简单效果实现	363

12.1 点选	363

12.1.1	透明的概念	363

12.2 输入	363

12.2.1	透明的概念	363

12.3 相加	363

12.3.1	透明的概念	363

第十二章 声音和特效	364

11.1 XXX	364

11.1.1	xxx简述	364

第三部分 DirectX12 UWP进阶	365

第X章 DAE Collada模型	365

X.1 模型加载库	365

X.1.1	Assimp和FBX SDK	365

X.1.2	DAE Collada模型文件简介	367

X.1.3	如何获取DAE Collada模型文件	368

X.2 DAE Collada剖析	368

X.2.1	DAE Collada结构	368

X.2.2	library_geometries节点	369

X.2.3	source节点剖析	370

X.2.4	triangles节点剖析	371

X.2.5	材质和纹理的节点剖析	372

X.3 渲染DAE Collada模型	373

X.3.1	使用XmILite解析DAE Collada文件	373

X.3.2	网格原始数据	375

X.3.3	构造网格	376

X.4 多个网格的DAE Collada模型	379

X.4.1	<library_visual_scenes>节点剖析	379

X.4.2	构造和渲染场景	381

第Y章 DAE Collada动画	383

y.3 DAE Collada动画	383

y.3.1	DAE Collada动画	383

第Z章 FBX模型	383

Z.1 XXX	383

Z.1.1	xxx简述	383

最初的BB：
我正在写的一本关于DirectX12的开发书籍《DirectX12 3D游戏程序设计》，这里是书中的例子。

