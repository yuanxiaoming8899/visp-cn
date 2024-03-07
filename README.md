<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ViSP：开源视觉伺服平台</font></font></h1><a id="user-content-visp-open-source-visual-servoing-platform" class="anchor" aria-label="永久链接：ViSP：开源视觉伺服平台" href="#visp-open-source-visual-servoing-platform"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://github.com/lagadic/visp/releases"><img src="https://camo.githubusercontent.com/a897722d684d26faf7c857c7ca3235bde04f65ae3185fb1162b7610b64c78c53/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f6c6167616469632f766973702e737667" alt="Github 发布" data-canonical-src="https://img.shields.io/github/release/lagadic/visp.svg" style="max-width: 100%;"></a>
<a href="https://opensource.org/license/gpl-2-0/" rel="nofollow"><img src="https://camo.githubusercontent.com/220363c265f01fcc2c4391699d5b80cda312329a41cf101f598712bc1ae88cf5/68747470733a2f2f656464656c6275657474656c2e6769746875622e696f2f6261646765732f47504c322b2e737667" alt="执照" data-canonical-src="https://eddelbuettel.github.io/badges/GPL2+.svg" style="max-width: 100%;"></a></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平台</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建状态</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ubuntu 20.04、22.04 (amd64)</font></font></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/ubuntu-dep-apt.yml"><img src="https://github.com/lagadic/visp/actions/workflows/ubuntu-dep-apt.yml/badge.svg" alt="ubuntu dep apt 工作流程" style="max-width: 100%;"></a> <a href="https://github.com/lagadic/visp/actions/workflows/ubuntu-dep-src.yml"><img src="https://github.com/lagadic/visp/actions/workflows/ubuntu-dep-src.yml/badge.svg" alt="ubuntu dep src 工作流程" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS 11 和 12</font></font></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/macos.yml"><img src="https://github.com/lagadic/visp/actions/workflows/macos.yml/badge.svg" alt="macOS 工作流程" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS 11.0 上的 iOS</font></font></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/ios.yml"><img src="https://github.com/lagadic/visp/actions/workflows/ios.yml/badge.svg" alt="ios工作流程" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 10</font></font></td>
<td><a href="https://ci.appveyor.com/project/fspindle/visp/branch/master" rel="nofollow"><img src="https://camo.githubusercontent.com/deb059727c800a53336eb47e5d3ca1bea7f54169e09a5d11989b3880fdf5adf7/68747470733a2f2f63692e6170707665796f722e636f6d2f6170692f70726f6a656374732f7374617475732f313231647363646b7279663564626e302f6272616e63682f6d61737465723f7376673d74727565" alt="构建状态" data-canonical-src="https://ci.appveyor.com/api/projects/status/121dscdkryf5dbn0/branch/master?svg=true" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他架构 Ubuntu 22.04（aarch64、s390x）</font></font></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/other-arch.yml"><img src="https://github.com/lagadic/visp/actions/workflows/other-arch.yml/badge.svg" alt="其他拱门工作流程" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS1 Noetic Ubuntu 20.04 Focal</font></font></td>
<td><a href="https://build.ros.org/job/Ndev__visp__ubuntu_focal_amd64/" rel="nofollow"><img src="https://camo.githubusercontent.com/7d32061ef577f276a11728be590db6bd45f8d3743467b69cef5ca307f0f7a792/68747470733a2f2f6275696c642e726f732e6f72672f6275696c645374617475732f69636f6e3f6a6f623d4e6465765f5f766973705f5f7562756e74755f666f63616c5f616d643634" alt="构建状态" data-canonical-src="https://build.ros.org/buildStatus/icon?job=Ndev__visp__ubuntu_focal_amd64" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS2 谦虚的 Ubuntu 22.04 Jammy</font></font></td>
<td><a href="https://build.ros2.org/job/Hdev__visp__ubuntu_jammy_amd64/" rel="nofollow"><img src="https://camo.githubusercontent.com/0921381ddbeada383e995c67b226b365ad8abc36be6e0cbcab91c5c66e29362e/68747470733a2f2f6275696c642e726f73322e6f72672f6275696c645374617475732f69636f6e3f6a6f623d486465765f5f766973705f5f7562756e74755f6a616d6d795f616d643634" alt="构建状态" data-canonical-src="https://build.ros2.org/buildStatus/icon?job=Hdev__visp__ubuntu_jammy_amd64" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS2 Iron Ubuntu 22.04 杰米</font></font></td>
<td><a href="https://build.ros2.org/job/Idev__visp__ubuntu_jammy_amd64/" rel="nofollow"><img src="https://camo.githubusercontent.com/e44ff8280ebdeb41419944b13b511a9c1bd4379a1cc26a7595c6d93fb468ee8e/68747470733a2f2f6275696c642e726f73322e6f72672f6275696c645374617475732f69636f6e3f6a6f623d496465765f5f766973705f5f7562756e74755f6a616d6d795f616d643634" alt="构建状态" data-canonical-src="https://build.ros2.org/buildStatus/icon?job=Idev__visp__ubuntu_jammy_amd64" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS2 滚动 Ubuntu 22.04 Jammy</font></font></td>
<td><a href="https://build.ros2.org/job/Rdev__visp__ubuntu_jammy_amd64" rel="nofollow"><img src="https://camo.githubusercontent.com/8354cf3ab09f771927f49733da95d4ebd921d5358d057075ea8c6ff125ebcc5b/68747470733a2f2f6275696c642e726f73322e6f72672f6275696c645374617475732f69636f6e3f6a6f623d526465765f5f766973705f5f7562756e74755f6a616d6d795f616d643634" alt="构建状态" data-canonical-src="https://build.ros2.org/buildStatus/icon?job=Rdev__visp__ubuntu_jammy_amd64" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">瓦尔格林德</font></font></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/valgrind.yml"><img src="https://github.com/lagadic/visp/actions/workflows/valgrind.yml/badge.svg" alt="valgrind 工作流程" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">消毒剂</font></font></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/ubuntu-sanitizers.yml"><img src="https://github.com/lagadic/visp/actions/workflows/ubuntu-sanitizers.yml/badge.svg" alt="消毒剂工作流程" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码覆盖率</font></font></td>
<td><a href="https://codecov.io/gh/lagadic/visp" rel="nofollow"><img src="https://camo.githubusercontent.com/ff30028ad1baa23c7fc2d331c81618d82c79e2f38feeb00123cfbeabe65d43ce/68747470733a2f2f636f6465636f762e696f2f67682f6c6167616469632f766973702f6272616e63682f6d61737465722f67726170682f62616467652e7376673f746f6b656e3d475149694b6241334243" alt="代码覆盖率" data-canonical-src="https://codecov.io/gh/lagadic/visp/branch/master/graph/badge.svg?token=GQIiKbA3BC" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他的项目</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建状态</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://github.com/lagadic/ustk"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌兹别克斯坦</font></font></a></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/macos-ustk.yml"><img src="https://github.com/lagadic/visp/actions/workflows/macos-ustk.yml/badge.svg" alt="苹果系统" style="max-width: 100%;"></a> <a href="https://github.com/lagadic/visp/actions/workflows/ubuntu-ustk.yml"><img src="https://github.com/lagadic/visp/actions/workflows/ubuntu-ustk.yml/badge.svg" alt="乌班图" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><a href="https://github.com/lagadic/visp_contrib"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">visp_contrib</font></font></a></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/ubuntu-contrib.yml"><img src="https://github.com/lagadic/visp/actions/workflows/ubuntu-contrib.yml/badge.svg" alt="乌班图" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><a href="https://github.com/lagadic/visp_sample"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">visp_样本</font></font></a></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/macos.yml"><img src="https://github.com/lagadic/visp/actions/workflows/macos.yml/badge.svg" alt="macOS 工作流程" style="max-width: 100%;"></a> <a href="https://github.com/lagadic/visp/actions/workflows/ubuntu-dep-apt.yml"><img src="https://github.com/lagadic/visp/actions/workflows/ubuntu-dep-apt.yml/badge.svg" alt="ubuntu dep apt 工作流程" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><a href="https://github.com/lagadic/camera_localization"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相机定位</font></font></a></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/ubuntu-3rdparty.yml"><img src="https://github.com/lagadic/visp/actions/workflows/ubuntu-3rdparty.yml/badge.svg" alt="ubuntu_3rdparty_工作流程" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><a href="https://github.com/lagadic/visp_started"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">visp_启动</font></font></a></td>
<td><a href="https://github.com/lagadic/visp/actions/workflows/ubuntu-3rdparty.yml"><img src="https://github.com/lagadic/visp/actions/workflows/ubuntu-3rdparty.yml/badge.svg" alt="ubuntu_3rdparty_工作流程" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://team.inria.fr/rainbow" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ViSP 是一个跨平台库（Linux、Windows、MacOS、iOS、Android），允许使用视觉跟踪和视觉伺服技术进行原型设计和开发应用程序，这是 Inria Rainbow 团队</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在和</font></font><a href="https://team.inria.fr/lagadic" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lagadic 团队</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 2018 年之前所做的研究的核心</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">ViSP 能够计算可应用于机器人系统的控制定律。</font><font style="vertical-align: inherit;">它提供了一组可以使用实时图像处理或计算机视觉算法进行跟踪的视觉特征。</font><font style="vertical-align: inherit;">ViSP 还提供模拟功能。</font><font style="vertical-align: inherit;">ViSP 可用于机器人、计算机视觉、增强现实和计算机动画。</font><font style="vertical-align: inherit;">我们的</font></font><a href="https://www.youtube.com/user/VispTeam" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YouTube 频道</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概述了可以解决的应用程序。</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用 ViSP</font></font></h4><a id="user-content-citing-visp" class="anchor" aria-label="永久链接：引用 ViSP" href="#citing-visp"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://inria.hal.science/inria-00351899" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果ViSP</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对您的研究有帮助，请在您的出版物中</font><font style="vertical-align: inherit;">引用它：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@article{Marchand05b,
   Author = {Marchand, E. and Spindler, F. and Chaumette, F.},
   Title = {ViSP for visual servoing: a generic software platform with a wide class of robot control skills},
   Journal = {IEEE Robotics and Automation Magazine},
   Volume = {12},
   Number = {4},
   Pages = {40--52},
   Publisher = {IEEE},
   Month = {December},
   Year = {2005}
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@article{Marchand05b,
   Author = {Marchand, E. and Spindler, F. and Chaumette, F.},
   Title = {ViSP for visual servoing: a generic software platform with a wide class of robot control skills},
   Journal = {IEEE Robotics and Automation Magazine},
   Volume = {12},
   Number = {4},
   Pages = {40--52},
   Publisher = {IEEE},
   Month = {December},
   Year = {2005}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用</font></font><a href="https://inria.hal.science/hal-01853972v1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于模型的通用跟踪器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@InProceedings{Trinh18a,
   Author = {Trinh, S. and Spindler, F. and Marchand, E. and Chaumette, F.},
   Title = {A modular framework for model-based visual tracking using edge, texture and depth features},
   BookTitle = {{IEEE/RSJ Int. Conf. on Intelligent Robots and Systems, IROS'18}},
   Address = {Madrid, Spain},
   Month = {October},
   Year = {2018}
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@InProceedings{Trinh18a,
   Author = {Trinh, S. and Spindler, F. and Marchand, E. and Chaumette, F.},
   Title = {A modular framework for model-based visual tracking using edge, texture and depth features},
   BookTitle = {{IEEE/RSJ Int. Conf. on Intelligent Robots and Systems, IROS'18}},
   Address = {Madrid, Spain},
   Month = {October},
   Year = {2018}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用姿态估计算法和</font><font style="vertical-align: inherit;">通过</font><a href="https://github.com/lagadic/camera_localization"><font style="vertical-align: inherit;">ViSP 示例说明的</font></a></font><a href="https://hal.science/hal-01246370v1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实践调查</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://github.com/lagadic/camera_localization"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@article{Marchand16a,
   Author = {Marchand, E. and Uchiyama, H. and Spindler, F.},
   Title = {Pose estimation for augmented reality: a hands-on survey},
   Journal = {IEEE Trans. on Visualization and Computer Graphics},
   Volume = {22},
   Number = {12},
   Pages = {2633--2651},
   Month = {December},
   Year = {2016}
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@article{Marchand16a,
   Author = {Marchand, E. and Uchiyama, H. and Spindler, F.},
   Title = {Pose estimation for augmented reality: a hands-on survey},
   Journal = {IEEE Trans. on Visualization and Computer Graphics},
   Volume = {22},
   Number = {12},
   Pages = {2633--2651},
   Month = {December},
   Year = {2016}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">资源</font></font></h4><a id="user-content-resources" class="anchor" aria-label="永久链接：资源" href="#resources"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主页： https: </font></font><a href="https://visp.inria.fr" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//visp.inria.fr</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维基：https: </font></font><a href="https://github.com/lagadic/visp/wiki"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//github.com/lagadic/visp/wiki</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码文档：</font></font><a href="https://visp-doc.inria.fr/doxygen/visp-daily" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://visp-doc.inria.fr/doxygen/visp-daily</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问答论坛： https: </font></font><a href="https://github.com/lagadic/visp/discussions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//github.com/lagadic/visp/discussions</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题跟踪： https: </font></font><a href="https://github.com/lagadic/visp/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//github.com/lagadic/visp/issues</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YouTube： https: </font></font><a href="https://www.youtube.com/user/VispTeam" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//www.youtube.com/user/VispTeam</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h4><a id="user-content-contributing" class="anchor" aria-label="永久链接：贡献" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请在开始处理拉取请求之前阅读：</font></font><a href="https://visp.inria.fr/contributing-code/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://visp.inria.fr/contributing-code/</font></font></a></p>
</article></div>
