#### 基于前馈模型算法的精细化三维场景重构
利用前馈模型预测的射线场作为几何约束基础，结合路径一致性进行全局图优化，采用由粗到细的点云拼接方法，实现全局一致的像素级点云建图。最终构建colamp格式数据进行高斯训练渲染。

<div align="center">
    <img src="static/assets/img/001.png" alt="我的照片" width="1260" style="border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); margin: 20px 0;">
</div>
<div align="center">
    基于单目RGB图像的真实场景（东北大学校园）无人机重建效果
</div>


<div align="center">
<img src="/static/assets/img/001.gif"
     alt="基于单目RGB图像的KITTI00数据集长序列点云效果（单张24g3080显卡）"
     width="800"
     style="border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); margin: 20px 0;">

</div>

<div align="center">
     基于单目RGB图像的KITTI01数据集长序列重建效果

</div>
<!-- MP4 视频 -->
<div align="center">
    <video width="800" autoplay loop muted playsinline
           style="border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); margin: 20px 0;">
        <source src="/static/assets/img/001.mp4" type="video/mp4">
        您的浏览器不支持 video 标签
    </video>
</div>
<div align="center">
    无人机32张RGB图训练视角帧间插值10张高斯渲染视频效果
</div><br>


#### 端到端自动驾驶 VLA 模型实践
设计并跑通了一套从 nuScenes 原始数据提取到多模态大模型指令微调的技术闭环。融合视觉感知与车辆运动学状态的混合指令数据问答对。成功让 3B 模型具备了理解物理状态并预测未来轨迹的能力。

<!-- MP4 视频 -->
<div align="center">
    <video width="800" autoplay loop muted playsinline
           style="border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); margin: 20px 0;">
        <source src="/static/assets/img/003.mp4" type="video/mp4">
        您的浏览器不支持 video 标签
    </video>
</div>
<div align="center">
    基于Qwen2.5-VL-3B的VLA轨迹预测
</div><br>

#### 面向增强现实的三维场景实景映射技术研究
使用SuperPoint特征点提取稠密特征，加入基于阈值的暗光增强方法，并基于 deeplab 语义分割模型进行语义提取，利用二维语义到 3D 点云映射构建场景的语义点云图及二维栅格地图。

<!-- MP4 视频 -->
<div align="center">
    <video width="800" autoplay loop muted playsinline
           style="border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); margin: 20px 0;">
        <source src="/static/assets/img/004.mp4" type="video/mp4">
        您的浏览器不支持 video 标签
    </video>
</div>
<div align="center">
    基于SuperPoint特征点的稠密、语义点云生成。
</div><br>

#### 基于虚拟现实的资源终端敏捷接入与态势交互
基于Mirror进行unity的多人联机操控编程，并将建好的mesh地形图导入unity中进行交互演示。

<!-- MP4 视频 -->
<div align="center">
    <video width="800" autoplay loop muted playsinline
           style="border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); margin: 20px 0;">
        <source src="/static/assets/img/005.mp4" type="video/mp4">
        您的浏览器不支持 video 标签
    </video>
</div>
<div align="center">
    基于Mirror的局域网多人联机操控
</div><br>



