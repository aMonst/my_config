# VSVim 相关配置
VSVim 需要Visual Studio的版本在Visual Studio 15以上。安装上插件之后某些快捷键会跟Visual Studio原生快捷键冲突，可以在 工具-->选项-->VSVim-->keyboard 中选择某些快捷键应用于VSVim或者是VS。

VSVim 默认的配置文件在 \~/_vimrc 中，这里我没有找到如何修改配置文件的路径，我在\~/_vimrc 文件中加了一句
```
source ~/.config/VisualStudio/_vimrc
```
来使VSVim 读取我这个位置的配置
