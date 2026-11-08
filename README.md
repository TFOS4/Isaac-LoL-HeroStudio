# Isaac-LoL-HeroStudio

本工具可以从本机《英雄联盟》客户端提取英雄素材，预览模型和动画、调整数值、选择商店装备，并导出完整制作包交给 Agent 完成 Mod。

制作包包含素材、框架代码、用户配置和制作说明，无需手动整理模型文件。

## 如何使用

1. 解压工具压缩包，运行 `HeroStudio.exe`。
2. 选择本机《英雄联盟》客户端目录和英雄，需要时开启皮肤读取。
3. 预览模型和动画，调整属性并选择商店装备。
4. 导出制作包，交给支持读取文件和修改代码的 Agent。

工具支持中英文界面，英雄名称提供中英对照，装备支持物理系、法系预设及手动选择。

## 安装与运行

需要 Windows 64 位、《以撒的结合：忏悔+》和 REPENTOGON，显卡驱动需支持 OpenGL 3.3。

Agent 完成制作后，应提供可安装包及中英双语 `INSTALL.txt`。

1. 将英雄 Mod 文件夹放入以撒的 `mods` 目录，确保 `main.lua` 直接位于英雄文件夹内，不要多套一层目录。
2. 完整解压 Companion 配套包，退出游戏并运行安装器。
3. 确认游戏目录和实际使用的 REPENTOGON 运行目录，点击安装。
4. 通过 REPENTOGON 启动游戏，启用 Mod 并选择对应英雄。

进入房间后，看到清晰的实时 3D 模型和专属界面，即可确认配套程序正常工作。具体安装器名称和文件夹位置以 `INSTALL.txt` 为准。

## 附带示例

`Nasus-Example.zip`：狗头 Nasus 示例 Mod，可直接安装体验，也可作为英雄制作参考。同样需要安装 Companion 配套程序。

## 版权说明

本项目为非官方玩家工具，与 Riot Games、Nicalis 及 Edmund McMillen 无关。英雄模型、动画、音效等素材归各自权利方所有，来源与署名见随包文件。


# Isaac-LoL-HeroStudio

This tool extracts champion assets from your local League of Legends installation. You can preview models and animations, customize stats, select shop items, and export a development package for an Agent to complete the mod.

The package includes assets, framework code, configurations, and development instructions. No manual model file organization is required.

## How to Use

1. Extract the tool package and run `HeroStudio.exe`.
2. Select your local League of Legends directory and a champion. Enable skin extraction if needed.
3. Preview models and animations, adjust stats, and select shop items.
4. Export the package and give it to an Agent capable of reading files and modifying code.

The tool supports Chinese and English interfaces, bilingual champion names, and both physical and magic item presets, as well as manual selection.

## Installation

Requirements: Windows 64-bit, The Binding of Isaac: Repentance+, REPENTOGON, and OpenGL 3.3 compatible graphics support.

After development, the Agent should provide an installable mod package and a bilingual `INSTALL.txt`.

1. Place the champion mod folder inside Isaac's `mods` directory. Make sure `main.lua` is directly inside the champion folder, without an extra nested folder.
2. Fully extract the Companion package, close the game, and run its installer.
3. Verify the game directory and the actual REPENTOGON runtime directory, then click Install.
4. Launch the game through REPENTOGON, enable the mod, and select the champion.

After entering a room, a clear real-time 3D model and dedicated interface should appear. This confirms that the Companion program is working correctly. Refer to `INSTALL.txt` for exact folder and installer names.

## Included Example

`Nasus-Example.zip`: A playable Nasus example mod and a reference for creating other champions. It also requires the Companion package.

## Credits & Disclaimer

This is an unofficial fan-made tool and is not affiliated with Riot Games, Nicalis, or Edmund McMillen. All champion models, animations, audio, and related assets belong to their respective rights holders. Sources and credits are included in the package.
