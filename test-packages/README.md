# Desktop Organizer 分割线修复测试包

下载本目录的 `DesktopOrganizerPrototype_DividerFix_Windows_Test.zip`，完整解压后双击 `run.cmd`。

需要 Windows 11 x64 和 .NET 10 Windows Desktop Runtime。包内包含完整源码，安装 .NET 10 SDK 后也可用 `build.cmd` 自行编译。

验证状态：Linux 云端 Windows 目标交叉编译通过，0 错误、0 警告；25 项布局算法回归测试通过。Windows 实机启动、鼠标拖动、交点右键菜单和应用重启交互验收尚未执行。这是待实机验证的候选修复，不是已全部验收的正式版本。

完整日志、修改清单和实机验收步骤在 ZIP 中的 `DIVIDER_FIX_REPORT.md`。

ZIP SHA256：`a8a5adc3804c551d35fd0039b7306056de53503397e95d07d8be7e0fb1ec5ca6`
