# Allagan Tools CN

Allagan Tools v1.15.1.2 国服库存修复测试版，适用于国服卫月 API 15。修复打开雇员道具栏和部队储物柜后库存未录入的问题。实测客户端构建为 `2026.11.03.0000.0000`。

## 通过卫月安装

1. 打开 `/xlsettings`，在实验性功能中找到「自定义插件仓库」。
2. 添加下面的链接并保存。

```text
https://raw.githubusercontent.com/Alittlerecallinglittlebrother/AllaganTools-CN/main/repo.json
```

3. 打开 `/xlplugins`，搜索 **Allagan Tools CN** 并安装。启用前请停用已启用的 Allagan Tools，避免两份实例同时扫描库存。
4. 打开要录入的雇员道具栏和部队储物柜页面。到插件的 **Data → Characters/Retainers** 查看对应库存。

## 本地开发者安装

从 [本版本发布页](https://github.com/Alittlerecallinglittlebrother/AllaganTools-CN/releases/tag/v1.15.1.2) 下载开发者 ZIP，解压整个压缩包，在卫月的本地插件设置中选择 `InventoryToolsCN.dll`。

## 源码与许可

作者为 Critical_Impact。此版本基于 [Critical-Impact/InventoryTools](https://github.com/Critical-Impact/InventoryTools)，按 GPL-3.0 分发。对应源码和校验值见[本版本发布页](https://github.com/Alittlerecallinglittlebrother/AllaganTools-CN/releases/tag/v1.15.1.2)。包内 `LICENSES/DEPENDENCIES.md` 提供运行依赖的来源、版本与许可。
