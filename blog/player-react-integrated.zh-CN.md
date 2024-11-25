# 3D架构图软件 iCraft Editor 正式发布 @icraft/player-react 前端组件, 轻松嵌入3D架构图到您的项目，实现数字孪生

## 介绍

@icraft/player-react 是 iCraft Editor 全新推出的 React 组件库，专为简化3D数字孪生场景的前端集成而设计。通过该组件，开发者可以轻松地将 iCraft Editor 制作的3D场景无缝嵌入到 React 项目中，并获得丰富的交互能力和实时数据集成特性。


## 特性

- 🚀 **开箱即用** - 零配置集成，几行代码即可快速接入
- 🎨 **自定义插件集** - 支持通过灵活的插件机制集成可选功能
- 🔌 **实用的事件和方法** - 提供丰富的事件和方法，方便与您的项目集成
- 🎬 **动画控制** - 支持自动播放、循环播放等动画控制
- 🔌 **实时数据接入** - 支持实时数据接入，实现数字孪生


## 安装

```bash
pnpm install @icraft/player-react --save
```

## 使用

只需几行代码，即可在您的 React 项目中集成3D场景：

```tsx
import { ICraftPlayer } from "@icraft/player-react";
 
export default function MyScene() {
  return <ICraftPlayer src='your-scene.iplayer' />;
}
```

> **重要提示**: `.iplayer` 文件需要从 iCraft Editor 中导出，这是一个经过优化的3D场景文件格式，包含了场景的完整信息。您可以在 iCraft Editor 中编辑场景后，通过"导出"功能获取该文件。

## 示例

### 服务状态监控
展示如何将服务器集群的运行状态数据实时展示在3D场景中，包括CPU使用率、内存占用、运行时间等关键指标的可视化展示。
![服务器状态监控](https://raw.githubusercontent.com/gantFDT/icraft/refs/heads/main/public/images/website/server.webp)
  
[查看详情](https://icraft.gantcloud.com/player-react/example/serverstatus)

### 海外电商实时数据
展示如何将电商平台的实时交易数据、用户访问量、订单状态等信息映射到3D场景中，实现业务数据的可视化监控。
![海外电商实时数据](https://raw.githubusercontent.com/gantFDT/icraft/refs/heads/main/public/images/website/E-commerce.webp)
  
[查看详情](https://icraft.gantcloud.com/player-react/example/ecommerce)

### 炼化工厂实时生产数据
展示如何将工业生产环境中的设备运行状态、生产数据等实时展示在3D场景中，实现工业数字孪生。
![炼化工厂实时生产数据](https://raw.githubusercontent.com/gantFDT/icraft/refs/heads/main/public/images/website/Refining.webp)

[查看详情](https://icraft.gantcloud.com/player-react/example/refinery)


## 总结
@icraft/player-react 为开发者提供了一站式的3D数字孪生可视化解决方案。通过简单的配置即可快速构建专业的3D可视化应用，配合灵活的API和实时数据接入能力，让您的数字孪生项目快速落地。无论是监控大屏、运营分析，还是工业互联网应用，@icraft/player-react 都能助您轻松实现。

无论是系统架构图、软件架构图、云架构图、IT架构图、部署架构图，还是3D结构图、网络架构图、网络拓扑图，都可以使用iCraft Editor来绘制并实现数字孪生。

立即开始使用 @icraft/player-react，探索数字孪生的无限可能！

https://icraft.gantcloud.com/player-react/intro
