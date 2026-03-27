#### 基于3dgs算法的精细化三维场景重构
&emsp;&emsp;利用DepthanythingV3获取单目深度，构建全局一致的稠密点云，并利用Colmap计算每张图片的位姿和去畸变图像，最后总体作为输入进行高斯训练和渲染。

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 20px 0;">
    
    <div style="flex: 1; max-width: 600px; display: flex; flex-direction: column; align-items: center;">
        <img src="static/assets/img/building_point.png" alt="东北大学综合楼稀疏重建"
             style="width: 100%; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2);">
        <div style="text-align: center; margin-top: 10px;">
            东北大学综合楼稀疏重建效果
        </div>
    </div>

    <div style="flex: 1; max-width: 600px; display: flex; flex-direction: column; align-items: center;">
        <video autoplay loop muted playsinline preload="auto"
               style="width: 100%; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2);">
            <source src="static/assets/img/building-3dgs.mp4" type="video/mp4">
            您的浏览器不支持 video 标签
        </video>
        <div style="text-align: center; margin-top: 10px;">
            东北大学综合楼3DGS重建效果
        </div>
    </div>

</div><br>


<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 20px 0;">
    
    <div style="flex: 1; max-width: 600px; display: flex; flex-direction: column; align-items: center;">
        <img src="static/assets/img/dense_construction.png" alt="室内锅炉房稀疏重建"
             style="width: 100%; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2);">
        <div style="text-align: center; margin-top: 10px;">
            基于单目RGB图像的真实场景（室内锅炉房）稀疏重建效果
        </div>
    </div>

    <div style="flex: 1; max-width: 600px; display: flex; flex-direction: column; align-items: center;">
        <video autoplay loop muted playsinline preload="auto"
               style="width: 100%; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2);">
            <source src="static/assets/img/3dgs.mp4" type="video/mp4">
            您的浏览器不支持 video 标签
        </video>
        <div style="text-align: center; margin-top: 10px;">
            基于单目RGB图像的真实场景（室内锅炉房）3dgs重建效果
        </div>
    </div>

</div><br>

#### 端到端自动驾驶 VLA 模型实践
&emsp;&emsp;设计并跑通了一套从 NuScenes 原始数据提取到多模态大模型指令微调的技术闭环。融合视觉感知与车辆运动学状态的混合指令数据问答对。成功让 3B 模型具备了理解物理状态并预测未来轨迹的能力。

<!-- MP4 视频 -->
<div align="center">
    <video width="800" autoplay loop muted playsinline
           style="border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); margin: 20px 0;">
        <source src="static/assets/img/vla.mp4" type="video/mp4">
        您的浏览器不支持 video 标签
    </video>
</div>
<div align="center">
    基于Qwen2.5-VL-3B的VLA轨迹预测
</div><br>

#### 面向增强现实的三维场景实景映射技术研究
&emsp;&emsp;使用SuperPoint特征点提取稠密特征，加入基于阈值的暗光增强方法，并基于 DeepLab 语义分割模型进行语义提取，利用二维语义到 3D 点云映射构建场景的语义点云图及二维栅格地图。

<!-- MP4 视频 -->
<div align="center">
    <video width="800" autoplay loop muted playsinline
           style="border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); margin: 20px 0;">
        <source src="static/assets/img/004.mp4" type="video/mp4">
        您的浏览器不支持 video 标签
    </video>
</div>
<div align="center">
    基于SuperPoint特征点的稠密、语义点云生成。
</div><br>


<div align="center">
    <img src="static/assets/img/octomap.png" alt="我的照片" style="width: 600px; max-width: 95%; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); margin: 20px 0;">
</div>
<div align="center">
    在TUM-RGBD（room1）栅格地图生成效果
</div>



