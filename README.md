# 🌌 HongChen Script Portal (红尘脚本入口)

> 红尘抢单脚本官方 3D 赛博朋克风格导航页。

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ 特性 (Features)

### 🎨 沉浸式视觉体验
- **3D 核心引擎**: 基于 **Three.js** 构建的旋转核心动画，配合 **UnrealBloom** 辉光后期处理，营造深邃的科幻氛围。
- **动态交互**: 粒子背景随鼠标微动，文字故障 (Glitch) 特效，扫描线与暗角滤镜。
- **响应式布局**: 使用 **Tailwind CSS** 构建，完美适配 4K 大屏、笔记本及移动端设备。

### ⚡ 核心功能
- **多线路智能切换**: 
  - 提供 "线路 1" 与 "线路 2" 验证服务器实时切换。
  - 自动更新脚本下载/验证地址，确保最佳连接速度。
- **全系列版本导航**: 
  - 集成红尘全系列脚本入口（怪兽、独眼蛇、玩偶、1H、778 等）。
  - 快速访问 **[使用教程]** 与 **[自动发卡]** 平台。
- **安全防护**: 内置反调试机制，保护页面逻辑不被轻易篡改。

## 🛠️ 技术栈 (Tech Stack)

- **Frontend**: HTML5, React 18 (ESM), Tailwind CSS
- **3D Graphics**: Three.js, Postprocessing
- **Environment**: 无需 Node.js 环境，纯静态单页应用 (SPA)。

## 🚀 快速开始 (Quick Start)

1. **克隆项目**
   ```bash
   git clone https://github.com/YourRepo/HongChen-Portal.git
   ```

2. **运行**
   - 推荐使用 VS Code 安装 **Live Server** 插件。
   - 右键 `index.html` -> `Open with Live Server`。
   - 或者直接双击 `index.html` 打开（部分 3D 资源加载可能受限于浏览器安全策略，建议使用本地服务器）。

## ⚠️ 注意事项

- 页面包含反调试代码（禁止右键、F12 等），开发时如需调试请注释掉相关代码块。
- 3D 场景对显卡有轻微要求，建议在开启硬件加速的浏览器中访问。

---
© 2024 HongChen Gaming. All Rights Reserved.
