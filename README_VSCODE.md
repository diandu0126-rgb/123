在 Visual Studio Code 中运行本项目：

1. 打开此仓库的文件夹（含 main.py）。
2. 安装并启用 Python 扩展（Microsoft 出品）。
3. 建议创建并激活 Python 虚拟环境：
   - Windows (PowerShell): python -m venv .venv; .\.venv\Scripts\Activate.ps1
   - macOS/Linux: python3 -m venv .venv; source .venv/bin/activate
4. 在 VS Code 中运行任务以安装依赖：菜单 Terminal -> Run Task -> Install requirements，或按 Ctrl+Shift+B（根据配置）。
5. 安装完成后，按 F5 或使用 Run -> Start Debugging（选择 "Python: Run main.py"），程序会在 VS Code 的集成终端中启动并打开 Pygame 窗口。

提示：如果 VS Code 未选择正确的 Python 解释器，请在右下角选择你的虚拟环境解释器。