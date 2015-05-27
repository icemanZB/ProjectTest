# Project
个人项目
https://github.com/icemanZB/Project

http://www.cnblogs.com/foreveryt/p/4077380.html 入门

http://gitbeijing.com/

客户端 添加项目三种方式(点击+号)

	add 输入路径添加本地项目
	create 创建一个项目
	clone 在github 上有自己的项目 已经导入 就clone到本地

changes 列出了修改文件列表，可以自己选择是否把修改的内容作为一个版本
	点击蓝色部分 变成绿色的话 这些代码就不会做成一个版本

undo 撤销上一次的版本，适合于没有同步的版本,如果版本已经提交到github上面了 就不能撤销
revert this commit 抵消了上个版本 (上个版本修改了什么就删除什么)

roll back to this commit 选中一个要的版本 (回滚到这个版本)

publish 发布项目
sync 同步

http://wuyuans.com/2012/05/github-simple-tutorial/

sublimetext brackethighlighter
http://www.dbpoo.com/sublime-text3-brackethighlighter/

"default": {
            "icon": "dot",
            // BH1's original default color for reference
            // "color": "entity.name.class",
            "color": "brackethighlighter.default",
            "style": "highlight"
        },


http://www.dbpoo.com/sublime-text3-brackethighlighter/


color highlighter
{
    "enabled": true,
    "style": "default",
    "icons": true,
    "ha_style": "",  // underlined_solid
    "argb": false,
    "icons_all": false,
    "default_keybindings": true,
    "convert_util_path" : "convert",
    "color_formats": [
        "white",
        "#FFF", "#FFFF", "#FFFFFF", "#FFFFFFFF",
        "rgb(255, 255, 255)",
        "rgba(255, 255, 255, 1.0)",
        "hsv(0, 0%, 100%)",
        "hsva(0, 0%, 100%, 1.0)",
        "hsl(0, 100%, 100%)",
        "hsla(0, 100%, 100%, 1.0)"
    ],
    "file_exts": [".css", ".sass", ".scss", ".less", ".styl", ".html", ".js", ".sublime-settings", ".tmTheme", ".erb", ".haml"]
}

user

{
	"caret_style": "smooth",
	"color_scheme": "Packages/Color Scheme - Default/Monokai.tmTheme",
	"draw_centered": false,
	"ensure_newline_at_eof_on_save": true,
	"fold_buttons": true,
	"font_size": 12,
	"ignored_packages":
	[
		"Vintage"
	],
	"line_padding_bottom": 1,
	"line_padding_top": 1,
	"scroll_past_end": true,
	"spell_check": false,
	"tab_completion": true,
	"tab_size": 2,
	"theme": "Soda Dark 3.sublime-theme",
	"translate_tabs_to_spaces": false,
	"trim_automatic_white_space": true,
	"trim_trailing_white_space_on_save": true
}
