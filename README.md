# Windows Folder Protect

<!-- WFP_PUBLIC_README_START -->
## Folder Protect V1.0

一个轻量的 Windows 文件夹加密工具。右键文件夹选择“加密文件夹”，设置密码后会生成同名 `.wfp` 加密文件。双击 `.wfp` 输入密码即可打开文件夹，正常新建、编辑或删除文件；用完点击“锁定”。右键 `.wfp` 选择“解密文件夹”，可输入原密码永久恢复普通文件夹。

### 下载与安装

1. 下载 [V1.0 安装包](./windows_folder_protect_V1.0.zip) 并解压。
2. 双击 `InstallFolderProtect.exe` 安装。目标电脑不需要 Python、Conda 或管理员权限。
3. Windows 11 的右键功能可能在“显示更多选项”中。

### 卸载

可在 Windows“已安装的应用”中卸载，或运行安装目录中的 `UninstallFolderProtect.exe`。卸载不会删除 `.wfp` 文件和个人文件。

### 使用提醒

- 解锁期间，文件夹是普通明文目录；操作完成后请点击“锁定”。
- 首次使用请先用测试文件夹验证，并备份重要数据。程序异常退出后，已解锁文件夹可能保持明文。
- 当前安装包尚未签名，Windows 可能显示“未知发布者”。请只从本仓库下载，并核对 [SHA-256 校验文件](./SHA256SUMS-v1.0.txt)。

本仓库提供安装包，源代码暂未在此公开。
<!-- WFP_PUBLIC_README_END -->
