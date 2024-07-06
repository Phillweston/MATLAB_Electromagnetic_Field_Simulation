# 基于 matlab 的电磁场与电磁波仿真代码目录

- 第一章，矢量分析

  |章小节|Matlab 名称|
  |-|-|
  |1、二维标量场的梯度场演示|A1_Gradient_Field|
  |2、标量场的等高线演示|A2_Contour_lines|
  |3、三维矢量场的散度演示|A3_Divergence|
  |4、三维矢量场旋度演示|A4_Curl|

- 第二章，静电场

  |章小节|Matlab 名称|
  |-|-|
  |5、利用 ode45 等绘制电力线|B1_Ode45|
  |6、利用 quiver 绘制电力线|B2_Quiver|
  |7、使用 streamline 绘制电力线|B3_Streamline|
  |8、静电型隐形衣演示|B4_Electrostatic Invisibility_Cloak|
  |9、静电型幻觉装置演示|B5_Electrostatic Illusion_Device|

- 第三章，静磁场

  |章小节|Matlab 名称|
  |-|-|
  |10、无线输电系统中互感器的科学计算|C1_Transformer|
  |11、磁偶极子的磁力线绘制|C2_Magnetic_Dipole|
  |12、同轴线内部的磁场分布|C3_Coaxial_Line|
  |13、亥姆霍兹线圈的磁力线|C4_Helmholtz_coil|
  |14、环形铁芯螺线管的磁场分布|C5_Toroidal_Inductor|
  |15、双根传输线对应的磁场分布|C6_Twin-lead_Transmission_Line|
  |16、各向同性的静磁隐形装置|C7_Isotropic_Static_Magnetic_Invisibility_Cloak|
  |17、各向同性的静磁幻觉装置|C8_Isotropic_Static_Magnetic_Illusion_Device|
  |18、静磁场中超导体的性质观察|C9_Superconductor|
  |19、各向同性的直流电型隐形装置|C10_Isotropic_DC_Electric_Invisibility_Cloak|

- 第四章，静态场的解法

  |章小节|Matlab 名称|
  |-|-|
  |20、利用 MATLAB 中特殊函数指令，绘制特殊函数。|D1_Special_Functions|
  |21、《科学》杂志上的电磁隐身衣演示|D2_Invisibility_Cloak_in_the_journal_"Science"|
  |22、《自然》杂志上的电磁隐身衣演示|D3_Invisibility_Cloak_in_the_journal_"Nature"|
  |23、 MATLAB 符号工具箱及其应用|D4_Symbolic_Toolbox|
  |24、各向异性的直流电型幻觉装置|D5_Anisotropic_DC_Electric_Illusion_Device|
  |25、各向异性的静磁幻觉装置|D6_Anisotropic_Static_Magnetic_Illusion_Device|
  |26、各向异性的静磁隐形装置|D7_Anisotropic_Isotropic_Static_Magnetic_Invisibility_Cloak|
  |27、利用 PDE 工具箱求解各类静态场问题|D8_PDE_Toolbox|

- 第五章，时变电磁场

  |章小节|Matlab 名称|
  |-|-|
  |28、法拉第电磁感应定律|E1_Faraday's_Law|
  |29、涡流测厚原理演示|E2_Eddy_Current_Thickness_Measurement|
  |30、涡流测距原理演示|E3_Eddy_Current_Distance_Measurement|
  |31、完美电磁隐身装置演示|E4_Perfect_Invisibility_Cloak|
  |32、PDE 工具箱求解波动方程演示|E5_Solving_the_Wave_Equation_with_the_PDE_Toolbox|

- 第六章，均匀平面电磁波

  |章小节|Matlab 名称|
  |-|-|
  |33、均匀平面波的传播|F1_Plane_Wave|
  |34、线性极化波的演示|F2_Linearly_Polarized_Wave|
  |35、圆形极化波的演示|F3_Circularly_Polarized_Wave|
  |36、椭圆极化波的演示|F4_Elliptically_Polarized_Wave|
  |37、矩形波导中的场分布|F5_Rectangular_Waveguide|
  |38、矩形谐振腔中的场分布|F6_Rectangular_Resonant|
  |39、电磁波在分界面处的反射和透射|F7_Reflection_and_Transmission|
  |40、左手材料的负折射特性演示|F8_Left-handed_Material|
  |41、表面等离激元的演示|F9_Surface_Plasmon|

- 第七章，电磁波的辐射

  |章小节|Matlab 名称|
  |-|-|
  |42、电偶极子天线的方向图演示（利用实时脚本等解析计算|G1_Dipole_Antenna|
  |43、半波振子天线的方向图演示（利用实时脚本等解析计算|G2_Half-Wave_Dipole_Antenna|
  |44、天线阵的方向图演示（利用实时脚本等解析计算|G3_Antenna_Array|
  |45、相控天线阵的动态演示（利用实时脚本等解析计算|G4_Phased_Array_Antenna|
  |46、偶极子天线的仿真（天线工具箱仿真计算|G5_Dipole_Antenna_Antenna_Toolbox|
  |47、半波振子天线的仿真（天线工具箱仿真计算）|G6_Half-Wave_Dipole_Antenna_Antenna_Toolbox|
  |48、八木天线的仿真（天线工具箱仿真计算）|G7_Yagi_Antenna_Antenna_Toolbox|
  |49、螺旋天线的仿真（天线工具箱仿真计算）|G8_Helical_Antenna_Antenna_Toolbox|
  |50、电磁超表面的远场方向图演示（利用实时脚本等解析计算）|G9_Metasurface|
  |51、天线阵的方向图演示（天线工具箱仿真计算）|G10_Antenna_Array_Antenna_Toolbox|

- 第八章，课程设计（1）

  |章小节|Matlab 名称|
  |-|-|
  |52、利用 PDE 工具箱和天线工具箱设计铁罐天线|H1_Metal_Can_Antenna|

- 第九章，课程设计（2）

  |章小节|Matlab 名称|
  |-|-|
  |53、利用天线工具箱设计微带贴片天线|I1_Microstrip_Patch_Antenna|