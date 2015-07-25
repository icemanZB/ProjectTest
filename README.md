# Project
个人项目
https://github.com/icemanZB/Project

http://www.cnblogs.com/foreveryt/p/4077380.html 入门

http://blog.csdn.net/xsckernel/article/details/9015367   git push 的问题 git clone git@github.com:icemanZB/Project.git

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


a 标签加背景 需要转 display:inline-block/block; 并且给宽高，才能看到效果
否则默认内容撑开高度宽度,导致图片显示不全，如果没有内容那么就不会显示任何东西
<div class="img">
     <img src="img/pic1.png" alt=""/>
     <a href="javascript:;"></a>
</div>

.img a{ width: 54px; height: 22px; background: url(../img/guanzhu.png) no-repeat; display: inline-block;}

text-align:justify
这个是属性是单词两端对齐的意思。 值 justify 可以使文本的两端都对齐。

display:table-cell属性指让标签元素以表格单元格的形式呈现，类似于td标签。目前IE8+以及其他现代浏览器都是支持此属性
的，但是IE6/7只能对你说sorry了，这一事实也是大大制约了display:table-cell属性在实际项目中的应用。
我们都知道，单元格有一些比较特别的属性，例如元素的垂直居中对齐，关联伸缩等，所以display:table-cell还是有不少潜在的使用价
值的
与其他一些display属性类似，table-cell同样会被其他一些CSS属性破坏，例如float,
position:absolute，所以，在使用display:table-cell与float:left或是position:absolute
属性尽量不用同用。设置了display:table-cell的元素对宽度高度敏感，对margin值无反应，响应padding属性，基本上就是活脱
脱的一个td标签元素了。

二、display:table-cell与大小不固定元素的垂直居中

使用display:table-cell让大小不固定元素垂直居中已经是很老的方法了，关于此应用，我已经在“大小不固定的图片、多行文字的水平垂直居中”这篇文章中有过介绍。

方便阅读，这里再次展示下代码：

/*这里的大小是根据高宽上限128像素图片设置的*/
div{display:table-cell; width:1em; height:1em; border:1px solid #beceeb; font-size:144px; text-align:center; vertical-align:middle;}
div img{vertical-align:middle;}


webstrom
js提示比较迟缓
File -> Code Completion -> Autopopup in 下 1000改为0

webstorm安装后的一些设置技巧：
如何更改主题（字体&配色）:
File -> settings -> Editor -> colors&fonts -> scheme name.主题下载地址
如何让webstorm启动的时候不打开工程文件：
File -> Settings->General去掉Reopen last project on startup.
如何完美显示中文：
File -> Settings->Appearance中勾选Override default fonts by (not recommended)，设置Name:NSimSun，Size:12
如何显示行号：
File -> Settings->Editor，”Show line numbers”打上勾，就显示行号了
如何代码自动换行：
File -> settings -> Editor “Use Soft Wraps in editor” 打上钩，代码就自动换行了
如何点击光标，显示在本行末尾：
File -> Settings->Editor “Allow placement of caret after end of line”去掉勾就行了。
如何修改快键键：
File -> Settings->Keymap，然后双击要修改快捷的功能会有提示框出来，按提示操作
换成自己熟悉编辑器的快键键：
File ->Settings->Keymap，支持像Visual Studio、Eclipse、NetBeans这样的主流IDE。
javascript类库提示。
File -> settings -> Javascript -> Libraries -> 然后在列表里选择自己经常用到的javascript类库，最后Download and Install就ok了.
在开发js时发现，需要ctrl + return 才能选候选项：
File -> Setting -> Editor -> Code Completion -> Preselect the first suggestion: “Smart” 改为 “Always”
js提示比较迟缓
File -> Code Completion -> Autopopup in 下 1000改为0
git配置：
File -> settings -> Editor -> github，进去改github的账户，如果没有git则不需要.
插件安装：
File ->plugins，然后就选择给力的插件们再安装.(“css-X-fire”插件,用于当使用firebug修改css属性时，编辑器内的css代码也会发生变化。）
以后更新


Ctrl + Alt + T
Surround with…（if, else, try, catch, for, etc）用 * 来围绕选中的代码行，（ * 包括 if 、 while 、 try catch 等）
Reformat code ctrl+shift+f
----------------------------------------------------------
所有的变量，在正式运行代码之前，都提前赋了一个值：未定义
所有的函数，在正式运行代码之前，都是整个函数块
遇到重名的：只留一个
变量和函数重名了，就只留下函数


防止域解析出现偏差 ,尽量不要在if for 中定义全局变量和函数
// alert(a);            // ...
alert( fn1 );       // FF 不能对下面的函数进行预解析



if( true ){
var a = 1;
function fn1(){
    alert(123);
}
}


0%任何数=0 0%3=0
1%3=1 2%3=2 3%3=0

var i=0;
i++;
if(i===5){
 i=0;
}

i%=5; 和上面的if是一样的


var a=12<90 &&20  // a=20

var a=120<90 &&20  // a=false

var b=120<90 || 20 ;  // b=20

var b=120<90 || 20>200; //b=false

var d=!200; // d=false; 数据类型转换


复合样式不要获取 background:url()
单一样式不要做判断 backgroundColor

定时器调用函数方法

图片使用inline-block  不知道为什么

C:\Users\zhoubing\AppData\Local\Microsoft\VisualStudio\11.0\Extensions\qjpjrjgw.1zi

Git warning push.default is unset
http://blog.csdn.net/exlsunshine/article/details/18988531

port 443: Timed out
http://blog.csdn.net/tingyuanss/article/details/43559979

webstrom 换主题
http://my.oschina.net/lee2013/blog/314051
a 标签加背景 需要转 display:inline-block/block; 并且给宽高，才能看到效果
否则默认内容撑开高度宽度,导致图片显示不全，如果没有内容那么就不会显示任何

东西
<div class="img">
     <img src="img/pic1.png" alt=""/>
     <a href="javascript:;"></a>
</div>

.img a{ width: 54px; height: 22px; background: url(../img/guanzhu.png) 

no-repeat; display: inline-block;}

text-align:justify 
这个是属性是单词两端对齐的意思。 值 justify 可以使文本的两端都对齐。

display:table-cell属性指让标签元素以表格单元格的形式呈现，类似于td标签。目

前IE8+以及其他现代浏览器都是支持此属性
的，但是IE6/7只能对你说sorry了，这一事实也是大大制约了display:table-cell属

性在实际项目中的应用。
我们都知道，单元格有一些比较特别的属性，例如元素的垂直居中对齐，关联伸缩等

，所以display:table-cell还是有不少潜在的使用价
值的
与其他一些display属性类似，table-cell同样会被其他一些CSS属性破坏，例如

float, 
position:absolute，所以，在使用display:table-cell与float:left或是

position:absolute
属性尽量不用同用。设置了display:table-cell的元素对宽度高度敏感，对margin值

无反应，响应padding属性，基本上就是活脱
脱的一个td标签元素了。

二、display:table-cell与大小不固定元素的垂直居中

使用display:table-cell让大小不固定元素垂直居中已经是很老的方法了，关于此应

用，我已经在“大小不固定的图片、多行文字的水平垂直居中”这篇文章中有过介绍

。

方便阅读，这里再次展示下代码：

/*这里的大小是根据高宽上限128像素图片设置的*/
div{display:table-cell; width:1em; height:1em; border:1px solid #beceeb; 

font-size:144px; text-align:center; vertical-align:middle;} 
div img{vertical-align:middle;}


webstrom
js提示比较迟缓
File -> Code Completion -> Autopopup in 下 1000改为0

webstorm安装后的一些设置技巧：
如何更改主题（字体&配色）:
File -> settings -> Editor -> colors&fonts -> scheme name.主题下载地址
如何让webstorm启动的时候不打开工程文件：
File -> Settings->General去掉Reopen last project on startup.
如何完美显示中文：
File -> Settings->Appearance中勾选Override default fonts by (not 

recommended)，设置Name:NSimSun，Size:12
如何显示行号：
File -> Settings->Editor，”Show line numbers”打上勾，就显示行号了
如何代码自动换行：
File -> settings -> Editor “Use Soft Wraps in editor” 打上钩，代码就自动

换行了
如何点击光标，显示在本行末尾：
File -> Settings->Editor “Allow placement of caret after end of line”去

掉勾就行了。
如何修改快键键：
File -> Settings->Keymap，然后双击要修改快捷的功能会有提示框出来，按提示操

作
换成自己熟悉编辑器的快键键：
File ->Settings->Keymap，支持像Visual Studio、Eclipse、NetBeans这样的主流

IDE。
javascript类库提示。 
File -> settings -> Javascript -> Libraries -> 然后在列表里选择自己经常用

到的javascript类库，最后Download and Install就ok了.
在开发js时发现，需要ctrl + return 才能选候选项： 
File -> Setting -> Editor -> Code Completion -> Preselect the first 

suggestion: “Smart” 改为 “Always”
js提示比较迟缓
File -> Code Completion -> Autopopup in 下 1000改为0
git配置：
File -> settings -> Editor -> github，进去改github的账户，如果没有git则不

需要.
插件安装：
File ->plugins，然后就选择给力的插件们再安装.(“css-X-fire”插件,用于当使

用firebug修改css属性时，编辑器内的css代码也会发生变化。）
以后更新


Ctrl + Alt + T
Surround with…（if, else, try, catch, for, etc）用 * 来围绕选中的代码行，

（ * 包括 if 、 while 、 try catch 等）
Reformat code ctrl+shift+f
----------------------------------------------------------
所有的变量，在正式运行代码之前，都提前赋了一个值：未定义
所有的函数，在正式运行代码之前，都是整个函数块
遇到重名的：只留一个
变量和函数重名了，就只留下函数


防止域解析出现偏差 ,尽量不要在if for 中定义全局变量和函数
// alert(a);			// ...
alert( fn1 );		// FF 不能对下面的函数进行预解析



if( true ){
var a = 1;
function fn1(){
	alert(123);
}	
}


0%任何数=0 0%3=0
1%3=1 2%3=2 3%3=0

var i=0;
i++;
if(i===5){
 i=0;
}

i%=5; 和上面的if是一样的


var a=12<90 &&20  // a=20

var a=120<90 &&20  // a=false

var b=120<90 || 20 ;  // b=20

var b=120<90 || 20>200; //b=false

var d=!200; // d=false; 数据类型转换


复合样式不要获取 background:url()
单一样式不要做判断 backgroundColor

定时器调用函数方法

图片使用inline-block  不知道为什么

C:\Users\zhoubing\AppData\Local\Microsoft\VisualStudio\11.0\Extensions

\qjpjrjgw.1zi

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
    "file_exts": [".css", ".sass", ".scss", ".less", ".styl", ".html", 

".js", ".sublime-settings", ".tmTheme", ".erb", ".haml"]
}

sublime-github
http://ce.sysu.edu.cn/hope/Item.aspx?id=109301


很不错的网站
http://codepen.io/hszy00232

csshake
http://i.aboutall.cn/csshake/
360奇舞团
http://www.75team.com/

requirejs 看下

ff 插件
网页截图 Page Speed ColorZilla HostAdmin LinrLightWeb MeasureIt YSlow 占时

无法使用

closest()
http://www.w3school.com.cn/jquery/traversing_closest.asp

webstrom keymap completion 设置代码提示快捷键
http://my.oschina.net/u/141149/blog/311288


transform-origin 有待研究

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- 针对移动端,页面的宽度强制去适应设备的宽度,缩放比例默认为1 -->
    <meta name="viewport" content="width=device-width, initial-scale=1">


-ms-text-size-adjust: none;
    /* 设置屏幕在旋转的时候文字大小不要发生改变 */
    -webkit-text-size-adjust: none;
    -moz-text-size-adjust: none;
    -o-text-size-adjust: none;

当一个东西往上走的时候建议设置bottom  定位元素
bottom: 0%;  一定是和父元素底对齐的
bottom: 100%;  父元素顶部对齐

http://www.17sucai.com/preview/1/2014-12-

23/ScatteredPolaroidsGallery/index.html  超炫的散列画廊特效


http://www.superslide2.com/index.html  jquery 插件

sublime text settings

{
	"caret_style": "smooth",
	"color_scheme": "Packages/Color Scheme - Default/Monokai 

Bright.tmTheme",
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


sublime text 3065 http://www.52pojie.cn/thread-290585-1-1.html

SublimeCodeIntel https://github.com/SublimeCodeIntel/SublimeCodeIntel

webstrom  inspections duplicated jquery / typo / missing font/ unused

http://sentsin.com/layui/laypage/ 分页控件
