# 沈涛

> <span class="icon">&#xe60f;</span> `13675795622`&emsp;&emsp;
> <span class="icon">&#xe7ca;</span> `619951393@qq.com`&emsp;&emsp;
> <span class="icon">&#xe600;</span> [jerrysheen](https://github.com/jerrysheen)

<img class="avatar" src="./cvpic.png">

## &#xe618; 工作经验

<div alt="entry-title">
    <h3>智明星通  <span style="font-size: 0.8em; font-weight: lighter; margin-left: 3px;">图形程序</span></h3> 
    <p>2021.01 - 至今</p>
</div>

作为中台引擎程序，负责项目组的渲染表现开发，美术规范制定，以及性能优化工作。

<div class="entry-title"  style="margin-top: 10px;">
   <h3>效果表现开发</h3>
</div>

参考市面竞品游戏方案，参与多个SLG渲染方案开发，保证表现效果以及性能均衡。
- SLG 阴影方案 :
     实时阴影方案，优化阴影精度，支持Shadow Cache。Occlusion Shadow方案，只用R8来表达阴影遮蔽。平面阴影方案。
- SLG 地形方案 ：参考重返帝国内城的九层地表混合方案，只需采样三张Albedo完成混合，并制作美术工具链，美术在原生Terrain上修改美术表现后可一键导出。
- SLG GPU Animation动画驱动方案
- SLG 3D角色渲染方案：配合TA制作头发，皮肤渲染方案。
- SLG 山、水体、湖泊、树木、迷雾渲染方案。
<div class="entry-title"  style="margin-top: 10px;">
    <h3>性能优化以及管线优化</h3>
</div>


通过unity性能工具，framedebugger， renderdoc， gears来进行各种分析、提升帧率，优化发热以及耗电。

<div style="margin-top: 5px;">

- 渲染优化</br>
    1. Drawcall优化：SRP Batch合批优化，大量物体进行GPU Instancing绘制，阴影Drawcall优化。
    2. 带宽优化：利用性能工具定位带宽具体消耗原因，并针对不同阶段，不同硬件单元产生的带宽问题进行优化。
    3. Shader优化：Shader计算复杂度，贴图采样数优化，真机异常排查，变体数量优化，分支优化，针对不同机型配置不同的LOD。
    4. Renderpass优化：去掉渲染流程中冗余的pass，优化RT格式
    5. LOD优化：在远距离视角下用高LOD，减少带宽消耗，减少小三角形渲染。
    6. 粒子系统优化：针对低端机减少粒子发射数，调整渲染层级优化合批。
    7. 资源优化：监测材质球变体开关是否合理，规范贴图压缩格式和mip格式是否开启读写，规范mesh压缩格式，是否有不合理的通道。
    8. 针对不同机型设置不同的机型分类，区分Shader LOD，RenderScale，粒子表现，RT size，是否启用RenderFeature。
- Unity渲染管线优化:
    1. 支持RenderScale不影响UI层。
    2. 管线内置Bloom高光闪烁优化。
    3. 根据项目需求合理开关管线配置，避免配置错误带来的性能影响。
- CPU端优化（较为薄弱）
    1. 内存优化以及GC优化

</div>
<br>
<br>
<br>
<br>
<br>
<br>
<br><br><br>

## &#xe635; 项目经历
<div class="entry-title"  style="margin-top: 15px;">
    <h3>公司项目《Age of Sea》</h3>
</div>

深度参与项目开发、针对面向国家主力机型进行渲染方案定制、性能调优分级，为项目上线保驾护航。
<br> 
成果：项目上线时，在低端机型(Mali-G72)fps为30帧，极端性能场景20帧+；超低端机型(PowerVR-GE8320)20帧+，极端性能场景15帧+。

<div style="margin-top: 5px;">

1. 针对T3国家低端机设置一套轻量级的Shader以及渲染流程，减轻项目在开发中产生渲染瓶颈的可能性。
2. 针对割草场景提供GPU Animation支持，并在项目后段参与割草场景性能优化，帮助项目组优化客户端逻辑，减少卡顿问题。
3. 定期对项目进行GPU性能分析，资源合规分析。优化Shader变体问题、渲染合批问题。
4. 提供项目组效果表现支持，卡通海水Shader，湖水stencil挖坑方案，昼夜切换shader。
</div>



<div class="entry-title" style="margin-top: 15px;">
    <h3>ShanEngine</h3>
    <a href="https://github.com/jerrysheen/ShanEngine">github.com/jerrysheen/ShanEngine</a>
</div>

C++17 | DirectX 12 | OpenGL | PBR  | 现代渲染管线

<div style="margin-top: 5px;">

- 渲染架构设计 ：RenderAPI→RHI→Graphics→Renderer→Scene。
- 资源管理系统 ：包含MaterialLibrary智能缓存、ShaderLibrary、.meta文件序列化和Assimp集成、压缩贴图加载。
- PBR渲染系统 ：
- 支持windows平台下一键部署： 使用premake5支持一键部署和编译。
</div>

## &#xe80c; 教育经历

<div class="entry-title">
    <h3>淡江大学 <span style="font-size: 0.8em; font-weight: lighter; margin-left: 8px;">中国台湾，资讯工程， 本科</span></h3>  
    <p>2015.09 - 2019.06</p>
</div>

<div class="entry-title">
    <h3>南加州大学 <span style="font-size: 0.8em; font-weight: lighter; margin-left: 9px;">美国，计算机科学，硕士</span></h3> 
    <p>2019.12 - 2021.12</p>
</div>


## &#xecfa; 专业技能
- 熟悉移动端GPU渲染管线，了解各个阶段可能会造成的性能瓶颈以及修复手段。熟悉手机端mali低端机gpu硬件架构。
- 各种Unity性能渲染工具使用、RenderDoc， Frame Debugger， Memory Profiler, AssetStudio，Arm Streamline profiler, UWA Gears。
- 熟练掌握URP Shader开发，日常工作中可使用C#开发。
- 熟悉opengl，正在学习D3D12，能够用C++实现demo中的小功能。
- 熟练使用AI代码工具辅助代码开发，进行代码优化、架构调整、代码辅助阅读
