align_tab 对齐插件
放到 首选项 - > 按键绑定-用户 里面
```
[
    {
        "keys": ["ctrl+alt+shift+k"], "command": "align_tab", //对齐插件 以 : 对齐
        "args" : {"user_input" : ":/f"}
    },
    {
        "keys": ["ctrl+alt+shift+d"], "command": "align_tab",//对齐插件 以 = 对齐
        "args" : {"user_input" : "=/f"}
    }
]
```

Pretty JSON  格式化 json格式  快捷键  ctrl + m + m (ctrl 按两下m)

Seti_UI 主题
设置主题 , 首选项 -> 设置-用户
```
{
	"color_scheme": "Packages/Seti_UI/Scheme/Seti.tmTheme",
	"detect_indentation": false,
	"font_size": 12,
	"ignored_packages":
	[
		"Vintage"
	],
	"tab_size": 4,
	"theme": "Seti.sublime-theme",
	"update_check": false,
	"word_wrap": "false"
}

```
