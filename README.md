使用go 1.25.6 for win7 版本进行编译，生成大量适合win7系统的程序。

<img width="407" height="796" alt="image" src="https://github.com/user-attachments/assets/aeb6936b-fbc6-4842-afab-4d6073c39901" />

1. 基础组件类 (学习核心)
这些程序展示了如何处理最基本的 UI 元素：
simple.exe: 最基础的入门示例，展示一个简单的列表选择。
textinput.exe: 经典的单行文本输入框，带光标闪烁效果。
textinputs.exe: 同时处理多个输入框（如表单）。
textarea.exe: 多行文本输入区，类似于终端里的记事本。
list-simple.exe / list-default.exe / list-fancy.exe: 从简单到复杂的列表展示，其中 fancy 版本带搜索和过滤功能。
table.exe / table-resize.exe: 终端表格，展示如何排列对齐数据以及如何动态调整列宽。

2. 动画与反馈类 (提升颜值)
如果你想让你的工具看起来很“高级”，重点看这些：
progress-animated.exe: 带动画效果的进度条。
progress-download.exe: 模拟下载场景的进度反馈。
progress-static.exe: 静态进度条展示。
spinner.exe / spinners.exe: 展示各种各样的“转圈圈”等待动画。
stopwatch.exe / timer.exe: 秒表和倒计时功能。

3. 高级交互类 (复杂功能)
这些程序展示了如何处理复杂的逻辑：
file-picker.exe: 一个运行在终端里的文件选择器。
autocomplete.exe: 输入时的自动补全功能。
chat.exe: 模拟聊天界面的气泡对话效果。
credit-card-form.exe: 一个漂亮的信用卡信息填写流程。
package-manager.exe: 模仿 Linux 包管理器（如 apt/brew）安装软件的综合演示。

4. 布局与系统控制类
tabs.exe: 顶部的选项卡切换布局。
split-editors.exe: 左右或上下分屏效果。
fullscreen.exe: 演示如何占据整个终端屏幕。
altscreen-toggle.exe: 演示如何在“主屏幕”和“备用屏幕”之间切换（类似 vim 打开和退出时的效果）。
window-size.exe: 实时检测并显示你手动拉伸终端窗口的大小。
mouse.exe: 演示如何在终端里捕捉鼠标点击和滚动事件。

5. 其他特殊演示
glamour.exe: 在终端里直接渲染漂亮的 Markdown 文档。
http.exe: 演示如何在 TUI 中处理异步网络请求。
exec.exe: 在 Bubble Tea 程序运行中途调用并执行其他的系统命令。
suspend.exe: 演示如何暂停当前 TUI 程序并挂起到后台。

💡 建议调试方法： 由于 Windows 7 的 CMD 限制，你可以优先运行 list-fancy.exe 或 package-manager.exe。如果这两个跑起来不乱码且动画流畅，说明你的环境已经完美适配 Bubble Tea 了。
