# PCLYachi Craft Launcher

基于 [Plain Craft Launcher (PCL)](https://github.com/Meloong-Git/PCL) 2.99.0.0 源代码修改的第三方版本，非官方发布，与原作者龙腾猫跃及其团队无关。

## 特性

- 白色磨砂玻璃界面：半透明卡片、侧栏与标题栏，背景图自动高斯模糊
- 支持自定义背景图（`PCL\Pictures`），可调模糊强度
- 配色可切换：蓝色 / 个性化
- 4px 圆角，精简了部分设置项与页面入口

## 许可

本项目遵循《PCL 分发有限许可》，详见仓库内 [LICENCE](LICENCE) 文件。源代码公开，并保留 PCL 原有的 Minecraft 正版购买劝导逻辑。

## 构建

环境：Windows 10/11、Visual Studio 2022/2026 生成工具（.NET Framework 4.8 目标包 + WPF/VB）、.NET SDK 9。

```powershell
git clone --recurse-submodules https://github.com/<你的用户名>/YCL.git
cd YCL

dotnet build PCLCS/PCLCS.csproj -c Release
msbuild "Plain Craft Launcher 2/Plain Craft Launcher 2.vbproj" -p:Configuration=Release -p:BuildProjectReferences=false
```

## 联系

- 版本号：1.68
- 项目地址：https://github.com/yachiyoCN/YCL
- 邮箱：yachi8000p@gmail.com
