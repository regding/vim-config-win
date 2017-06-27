# vim-config-win
### 简介
这是一个在Windows环境，基于gVim的vim配置。是为了将vim打造成一个Python IDE的vim配置。
主要配置过程参考如下文档链接。

### 使用到的插件（未使用插件管理软件，需要自己下载配置）
* [pydiction][] 丰富的的代码补全功能，按tab补全代码
* [Ctags for win][Ctags] 分析源代码的工具
* [TagList][]  配合Ctags可以高效的查看源代码
* [WinManager][]  窗口分栏显示插件
* [Cscope][]  更高级的分析源代码，支持反向查找 [Windows版下载][Cscope-win]
* [MiniBufExplorer][] 管理vim的buffer(缓冲区)，快速的在多个同时编辑的文件间切换
* [Grep][]  linux的grep [Windows版下载][Grep-win]


### 参考文档中提及，但未集成到本配置的插件
* VimPdb  可以调试Python程序，文档链接失效，无法下载，可自行Google搜索下载使用
* ropevim 重构Python程序
* [pyflakes][]  Python代码检查

### 参考文档
[Vim as Python IDE on windows][link1]

[pydiction]: http://www.vim.org/scripts/script.php?script_id=850
[Ctags]: http://ctags.sourceforge.net/
[TagList]: http://www.vim.org/scripts/script.php?script_id=273
[WinManager]: http://www.vim.org/scripts/script.php?script_id=95
[Cscope]: http://cscope.sourceforge.net/
[Cscope-win]: https://sourceforge.net/projects/mslk/
[MiniBufExplorer]: http://www.vim.org/scripts/script.php?script_id=159
[Grep]: http://www.gnu.org/software/grep/manual/
[Grep-win]: http://gnuwin32.sourceforge.net/packages/grep.htm
[pyflakes]: http://www.vim.org/scripts/script.php?script_id=2441

[link1]: http://www.cnblogs.com/renrenqq/archive/2010/09/09/1813669.html
