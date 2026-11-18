# Allagan Tools CN

Allagan Tools v1.15.1.3 国服库存修复测试版，适用于国服卫月 API 15。修复完整退出游戏再登录时，雇员和部队储物柜的已保存库存未恢复的问题。录入过的库存可在插件中直接查看。实测客户端构建为 `2026.11.03.0000.0000`。

## 通过卫月安装

1. 打开 `/xlsettings`，在实验性功能中找到「自定义插件仓库」。
2. 添加下面的链接并保存。

```text
https://raw.githubusercontent.com/Alittlerecallinglittlebrother/AllaganTools-CN/main/repo.json
```

3. 打开 `/xlplugins`，搜索 **Allagan Tools CN** 并安装。已通过这个在线库安装的用户可在卫月里更新。启用前请停用正在运行的其他 Allagan Tools 实例（包括本地开发者版），避免重复扫描库存。
4. 到插件的 **Data → Characters/Retainers** 查看已保存的库存。如果旧记录已丢失，打开对应的雇员道具栏和部队储物柜页面采集一次。

## 本地开发者安装

从 [本版本发布页](https://github.com/Alittlerecallinglittlebrother/AllaganTools-CN/releases/tag/v1.15.1.3) 下载开发者 ZIP，解压整个压缩包，在卫月的本地插件设置中选择 `InventoryToolsCN.dll`。

## 源码与许可

作者为 Critical_Impact。此版本基于 [Critical-Impact/InventoryTools](https://github.com/Critical-Impact/InventoryTools)，按 GPL-3.0 分发。对应源码和校验值见[本版本发布页](https://github.com/Alittlerecallinglittlebrother/AllaganTools-CN/releases/tag/v1.15.1.3)。包内 `LICENSES/DEPENDENCIES.md` 提供运行依赖的来源、版本与许可。
