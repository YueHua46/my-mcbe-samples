---
page_type: 示例
author: docsbryce
description: 资源包教程中使用的示例资源包。
ms.author: v-bbortree
ms.date: 2022/05/17
languages:
- json
products:
- minecraft
---

# 资源包示例

此示例是“资源包入门教程”中使用的资源包。

请参阅 [资源包入门](https://docs.microsoft.com/minecraft/creator/documents/resourcepack) 文档，了解如何将你的土块变成亮绿色的完整步骤。

## 使用资源包示例

资源包示例是完成资源包教程时检查你的工作的有用工具。使用它就像将它添加到你的 `development_resource_pack` 文件夹一样简单。

### 定位 com.mojang 文件夹

1. 按 Win+R 打开运行。
1. 将以下内容复制并粘贴到打开字段中：`%localappdata%\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang`
1. 点击确定。

### 将资源包示例复制到 `com.mojang` 文件夹

1. 点击 `development_resource_packs`。
1. 将 `resource_pack_sample` 复制到文件夹中。

### 在 Minecraft 中启用资源包

1. 启动 Minecraft 并选择 Play。
1. 选择 Create New World。
1. 在 Settings 下，滚动到 Add-Ons 部分。
1. 点击 Resource Packs 查看所有可用的包。
1. 点击 MY PACKS 下拉菜单以打开它。
1. 选择 My Resource Pack 并点击 Activate 将资源包添加到世界中。
1. 点击 Create 创建你的世界。

你的普通土块现在是亮绿色的。太棒了！

## 清单

- [textures/blocks/dirt.png](https://github.com/microsoft/minecraft-samples/blob/main/resource_pack_sample/textures/blocks/dirt.png): 一个新的亮绿色土质纹理，用于修改你世界中的现有块。
- [manifest.json](https://github.com/microsoft/minecraft-samples/blob/main/resource_pack_sample/manifest.json/): 这是示例资源包的 manifest.json 文件夹。