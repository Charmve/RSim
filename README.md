# RSIM
自动驾驶算法系列课程之《自动驾驶端到端闭环HIL仿真系统》Realtime HIL end-to-end closed-loop simulation system

<img src="https://research.zenseact.com/publications/neuro-ncap/assets/animated_overview.gif">

![image](https://github.com/Charmve/RSIM/assets/29084184/e04db905-15cd-48dc-b0ed-6da563815b74)


<h2 align="center">HIL：最有效的开发和测试</h2>

<table>
  <tbody>
    <tr>
      <td>
        节省时间
      </td>
      <td>
         降低成本
      </td>
      <td>
        降低风险，保障安全
      </td>
    </tr>
    <tr>
      <td>
        如今汽车、飞机和国防项目中日趋紧张的开发日程留给测试嵌入系统的开发原型时间不多。利用HIL技术可以极大地缩短开发时间：如若进行一款新型汽车发动机原型控制器测试，使用HIL仿真技术能够完成其中的95%测试任务。
      </td>
      <td>
        相对于高精度的实时仿真机而言，真实被测设备通常会更加昂贵。因此在产品开发和测试阶段，使用HIL仿真机比真实设备更加经济。
      </td>
      <td>
        HIL仿真技术可以让工程师轻松执行可能危及实际被测设备和测试工作人员人身安全的危险测试工况。因此，工程师们可以安心使用HIL技术进行各类危险工况测试，进而提升实际产品的安全性。
      </td>
    </tr>
  </tbody>
</table>


<h2>用于ADAS/AD开发的最具可扩展性、高保真度的传感器和环境模拟系统</h2>

![image](https://github.com/Charmve/RSIM/assets/29084184/99ef615d-0439-4c09-a881-8e73160d0e96)

![image](https://github.com/Charmve/RSIM/assets/29084184/a9d31acd-47a5-41ea-bfd8-46cc9c1b5630)


<h2>在HiL环境下基于场景进行实时ADAS/AD系统验证</h2>
12× 相机 + 6× 毫米波雷达实时运行展示

<table><tbody><tr>
  <td><img src="src/闭环HiL相机毫米波雷达实时运行展示-1.gif"></td>
  <td><img src="src/闭环HiL相机毫米波雷达实时运行展示-2.gif"></td>
</tr></tbody></table>

<h2>功能介绍</h2>
<table>
  <tbody>
    <tr>
      <td>
        <img src="https://github.com/Charmve/RSIM/assets/29084184/94d53e30-d10b-42da-a2e6-f355178a5062">
      </td>
      <td>
        <h4>多传感器仿真引擎</h4>
        <p>
          提供高质量的虚拟传感器数据流，同时优化资源使用，确保 ISO 26262 合规，具有高并行性、减少内存占用、平衡工作负载和异步数据传输等功能。
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <h4>大规模生成合成数据</h4>
        <p>
          重新定义了智能场景创建，具有场景变化、详细数据统计和直观用户界面等功能。同时，使用基于大型语言模型的技术，简化环境和场景创建，使智能场景更易访问。
        </p>
      </td>
      <td>
        <img src="https://github.com/Charmve/RSIM/assets/29084184/4f50bac4-d430-4222-a99e-7d2eef594f9d">
      </td>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/Charmve/RSIM/assets/29084184/d9fd7c6a-65d3-42b5-8b96-5f196fe77b41">
      </td>
      <td>
         <h4>可访问性和适应性显著提升</h4>
         <p>
           提供传感器仿真、场景和地图管理、车辆动力学等开放式API，配备全面SDK，能够无缝集成到行业标准工具链，具有更好的互操作性。同时，支持本地GUI部署和基于Web的云端部署，确保用户的良好体验。
         </p>
      </td>
    </tr>
    <tr>
      <td>
        <h4>AI算法生成场景编辑</h4>
         <p>
           随着外部渲染API的加入以及仿真引擎的高级能力，现在可以轻松地在由像 NeRF 或 3D Gaussian Splatting（3D高斯泼溅）等AI算法生成的逼真环境中进行混合交通场景的模拟。
         </p>
      </td>
      <td>
         <img src="https://github.com/Charmve/RSIM/assets/29084184/907a937b-0e45-482d-a5ac-062777f02aac">
      </td>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/Charmve/RSIM/assets/29084184/4a9ca498-95c0-47ce-a2a1-6307e9496354">
      </td>
      <td>
        <h4>自研引擎提供的确定性环境模拟</h4>
        <p>
          ADAS/AD开发依赖传感器感知环境。自研实时渲染引擎能够正确模拟相关传感器感知的环境，创建具备完全确定性和可重复性的物理环境和天气效应，始终为模拟的场景提供真实可靠的信息源，为基于神经网络的多传感器感知系统提供坚实基础。
        </p>
      </td>
    </tr>
  </tbody>
</table>

<h2>面向自动驾驶仿真的数字孪生世界建模与生成</h2>

<table><tbody><tr>
  <td><img src="https://github.com/Charmve/RSIM/assets/29084184/0cb668cc-fbbb-49bc-9034-0284f1c1906f"></td>
  <td><img src="https://github.com/Charmve/RSIM/assets/29084184/73f27738-9348-493e-9e0d-354be0e5816d"></td>
</tr></tbody></table>

https://github.com/wljungbergh/NeuroNCAP/assets/37999571/5725e2af-8215-4573-9372-c0ca8c03f5f0

## Ref
- https://keymotek.com/adas-simulator-aisim/
- NeuroNCAP: Photorealistic Closed-loop Safety Testing for Autonomous Driving. https://research.zenseact.com/publications/neuro-ncap/
- https://www.bilibili.com/video/BV1Aw4m1i7ep
- https://www.bilibili.com/video/BV1yw4m127Y9
- https://www.bilibili.com/video/BV15w41177Lo
- ClimateNeRF: Extreme Weather Synthesis in Neural Radiance Field. https://climatenerf.github.io/ 
