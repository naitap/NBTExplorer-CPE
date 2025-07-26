# NBTExplorer

NBTExplorer 是一个开源 NBT 编辑器，适用于所有常见的 NBT 数据来源。它主要用于编辑 [Minecraft](http://www.minecraft.net) 游戏数据.

该版本由 [NaiTap](https://space.bilibili.com/1076095077) 翻译并修复了部分漏洞

## 支持的格式

NBTExplorer 支持读取和写入以下格式：

* 标准 NBT 文件 (例如 level.dat)
* 原理图文件
* 未压缩的 NBT 文件 (例如 idcounts.dat)
* Minecraft 区域文件 (*.mcr)
* Minecraft 铁砧文件 (*.mca)
* 立方块区块文件 (r2*.mcr, r2*.mca)

## 系统要求

### Windows

Windows XP 或更高版本, .NET Framework 2.0 或更高版本.

### Linux

NBTExplorer 与最近的 Mono 运行时兼容，至少 2.6 或更高版本.
至少, 您的系统需要"单核"和"单核"包，或任何等效的包集.

### 苹果电脑

提供具有本机 UI 的单独 Mac 版本. 所有 Mono 依赖项都包含在应用程序包中.
最低支持的作系统是 OSX 10.8 Mountain Lion, 但它最早可以在 Snow Leopard 的版本上运行.

如果 Mac 版本无法运行, Windows 版本的 NBTExplorer 仍然可以使用. 您需要安装
Mono 运行时, 然后从命令行使用 Mono 运行 NBTExplorer.