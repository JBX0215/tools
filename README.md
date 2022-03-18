## Vscode settings.json 
### 特别说明
配置文件为json格式各字段含义说明。

### 字体
字体设置英文为Consolas 中文为 微软雅黑 ("editor.fontFamily": "Consolas, '微软雅黑', monospace")
字体大小设置("editor.fontSize": 14.5)

### 布局
终端侧边栏设置为右侧("workbench.sideBar.location": "right")

### 编辑器颜色
仅针对默认主题"[Default Light+]":{...}自定义设置, 去掉则为针对所有主题;
选中代码高亮颜色("editor.selectionHighlightBackground": "#f5f113")
选中区域背景色("editor.selectionBackground": "#f5f113")
设置背景色为护眼色("editor.background": "#cce8cf")
导航线背景色("editorGutter.background": "#cce8cf")
设置光标颜色("editorCursor.foreground": "#ff0000")
光标所在行四周边框的背景色("editor.lineHighlightBorder": "#d3d3d3")

### 代码颜色
注释:"comments": "#519657"
字符串: "strings": "#7e3648"
函数: "functions": "#1c7887"
关键字: "keywords": "#a207fc"
变量: "variables": "#0720fc"
数字: "numbers": "#e21d1d"

### 插件推荐
Bracket Pair Colorizer 括号自动识别匹配为不同颜色, 支持自定义, 极大的提高开发效率. This extension allows matching brackets to be identified with colours. The user can define which characters to match, and which colours to use.
