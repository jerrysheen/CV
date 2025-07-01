# 沈涛

> <span class="icon">&#xe60f;</span> `13675795622`&emsp;&emsp;
> <span class="icon">&#xe7ca;</span> `619951393@qq.com`&emsp;&emsp;
> <span class="icon">&#xe600;</span> [jerrysheen](https://github.com/jerrysheen)

<img class="avatar" src="https://avatars.githubusercontent.com/u/583231?v=4">

## &#xe618; 工作经验

<div alt="entry-title">
    <h3>智明星通  <span style="font-size: 0.8em; font-weight: lighter; margin-left: 3px;">图形程序</span></h3> 
    <p>2021.01 - 至今</p>
</div>

作为中台引擎程序，负责项目组的渲染表现开发，美术规范制定，以及性能优化工作。
<h4>效果表现开发</h4>

参考市面竞品游戏方案，参与开发多个SLG渲染方案，保证表现效果以及性能均衡。
- SLG 阴影方案
- SLG 地形方案
- SLG GPU Animation动画驱动方案
- SLG 3D角色渲染方案
- SLG 山、水体、湖泊、树木、迷雾渲染方案
- SLG UI飘字头顶血条方案

<h4>性能优化以及管线优化</h4>

- GPU渲染优化
通过unity性能工具，framedebug， renderdoc， gears来进行各种分析、提升帧率，优化发热以及耗电。
    1. 优化drawcall
    2. 显存优化
    3. shader优化，减少计算复杂度
    4. 优化RT格式，去掉渲染流程中冗余的pass以及rt，通过降低分辨率减少带宽和计算量消耗。
    5. LOD优化，减少小三角形的剔除，优化带宽以及运行时vs消耗。
- 内存优化
    1. 优化Unity Shader变体，减少shader内存以及shader warmup的内存。
- Unity渲染管线优化:
    1. 支持RenderScale不影响UI层
- CPU端优化（较为薄弱）
    1. 进组支持项目组工作，负责割草场景中的低端机性能优化
    对大量物体进行预生成和池化
    减少子弹检测逻辑，用BFS和简化碰撞检测。
    通过规范代码，减少运行时GC产生。

<h4>美术规范制定</h4>
这个地方其实可以写的是我Owner了这个项目的性能优化，比如针对这个项目我做了什么优化呢？直接来一个实战举例。
- 基于项目开发周期及主力机型，制定渲染方案:
针对公司开发产品很紧急的周期与美术共同定制了渲染方案，渲染流程，避免在开发中期产生的性能问题和调优。
    1.针对公司海外SLG产品，制定效果Shader，尽量减少开发过程中的GPU瓶颈，使得高中低端机型都能流畅渲染。
    2.制定高中低端机型渲染分级，表现优化。
    
- 明确项目内各种资源标准，注意事项。
    1. 明确各种性能指标，并负责日常指标检测，针对项目中因为版本迭代产生的渲染问题，进行及时的跟进调优。
    2. 与美术负责

## &#xe635; 项目经历

<div class="entry-title">
    <h3>ShanEngine</h3>
    <a href="https://github.com/jerrysheen/ShanEngine">github.com/jerrysheen/ShanEngine</a>
</div>
C++17 | DirectX 12 | OpenGL | PBR  | 现代渲染管线

<div style="margin-top: 5px;">

- 渲染架构设计 ：RenderAPI→RHI→Graphics→Renderer→Scene
- 完整前向渲染 ：CameraRenderer、RenderFeature模块化系统、Frustum Culling和渲染队列管理，支持多相机多渲染目标
- 资源管理系统 ：包含MaterialLibrary智能缓存、ShaderLibrary、.meta文件序列化和Assimp集成
- PBR渲染系统 ：
- 支持windows平台下一键部署： 使用premake5支持一键部署和编译
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
- 熟悉移动端GPU渲染管线，明确各个阶段可能会造成的性能瓶颈以及修复手段。基本明确手机端gpu硬件架构。
- 各种Unity性能渲染工具使用、RenderDoc， Frame Debugger， Memory Profiler, AssetStudio，远程调试工具，
- 熟练掌握C#和C++开发
- 熟练使用AI代码工具辅助代码开发，进行代码优化、架构调整、代码辅助阅读
- 熟悉美术工作开发流，以及项目组工作流
