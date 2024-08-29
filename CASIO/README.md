# CASIO Calculator Emulator
### V20.8.11
收集了所有截止至2020年8月11日CASIO公开发布过的函数型计算器模拟器，包含fx-ES系列，fx-ES PLUS系列，ClassWiz系列以及fx-ES PLUS (2nd Edition)系列。


## 介绍
### fx-ES 系列
包含以下5款模拟器

    fx-82ES
    fx-370ES
    fx-500ES
    fx-570ES
    fx-991ES

其中fx-82ES可在CASIO教育官网免费获取，其余4款在[cnCalc网站](https://www.cncalc.org/ "cnCalc网站")下载得，系根据fx-82ES的程序修改并替换界面图片得来。

### fx-ES PLUS系列
包含以下24款模拟器

    fx-82ES PLUS、fx-85ES PLUS、fx-350ES PLUS、fx-570ES PLUS、fx-991ES PLUS
    fx-82AU PLUS II、fx-100AU PLUS
    fx-520AZ
    fx-92 Collège 2D+、fx-92B Collège 2D+
    fx-82DE PLUS、fx-85DE PLUS、fx-86DE PLUS、fx-991DE PLUS
    fx-300ES PLUS、fx-991ES PLUS C、fx-115ES PLUS
    fx-83GT PLUS、fx-85GT PLUS
    fx-991ID PLUS
    fx-55 PLUS
    fx-96SG PLUS
    fx-570VN PLUS
    fx-82ZA PLUS

该模拟器仅在国外以光盘的形式发售，[ZhangYufeiC](https://tieba.baidu.com/home/main/?un=ZhangYufeiC 'ZhangYufeiC')购得后分享了ISO镜像。
提取出模拟器程序后，使用[user202729](https://tieba.baidu.com/home/main?un=user202729 'user202729')提供的破解方法完成破解：

    1.使用WinHEX等程序打开fx-***Emulator.exe
    2.转到偏移量34D2，将 E819010000 替换为 B801000000 （阻止错误弹窗）
    3.再转到偏移量34D9，将 0F8492000000 替换为 909090909090 （破解注册验证）

### ClassWiz系列
包含以下23\*款模拟器

    fx-82/350CN X, fx-991CN X
    fx-82/85/350EX, fx-570/991EX
    fx-82DE X, fx-87DE X, fx-991DE X
    fx-92B Spéciale Collège, fx-92+ Spéciale Collège
    fx-82/85/350SP X/X II, fx-570/991SP X/X II
    fx-82AR X, fx-95AR X, fx-570/991AR X
    fx-82/350LA X, fx-570/991LA X
    fx-82/85/350CE X, fx-991CE X
    fx-530AZ
    fx-97SG X
    fx-580VN X
    fx-83/85GT X
    fx-991RS X

\*注：

1.早期fx-530AZ是一同在[CASIO EDU官网](https://edu.casio.com/softwarelicense/index.php 'CASIO EDU')上发布、更新的，后被下架，
转为在[日本CASIO官网](https://edu.casio.com/all/update/manager_jp 'CASIO Japan')上更新，在这也一并收录。

2.fx-SP X系列推出后CASIO又推出了升级款fx-SP X II。升级款的各型号在功能方面没有变化，仅新增了一种界面语言。随后CASIO将SP X与SP X II的模拟器合并，
同时停止提供SP X系列型号模拟器的下载。故旧款SP X系列的两款模拟器（fx-82/350SP X与fx-570/991SP X）此处并未收录。

3.fx-92 Spéciale Collège（92SC）推出后，CASIO推出了fx-92B Spéciale Collège（92B）将其代替。两者的区别在于，
92SC不论是按键印刷还是程序界面均为法语，设置中无法更改程序语言；而92B的按键印刷采用了英文，有三种语言（法语、英语与荷兰语）供选择。
92B推出后CASIO即下架了92SC模拟器，故该模拟器也未收录。

4.以上三款未收录的模拟器原版可在[此处](https://pan-yz.chaoxing.com/external/m/file/500032212943761408 '超星网盘')下载

原版模拟器仅提供90天的试用，user202729提供了破解的方法。该方法在 Ver.02.01.0000.0000 下测试通过，不排除将来CASIO升级后失效的可能：

    1.使用WinHEX等程序打开fx-***Emulator.exe
    2.进行如下修改，搜索并替换：
      755C8D4D -> EB5C8D4D //解决同时只能打开一个模拟器的限制
      C0743F6A -> C0EB136A //跳过激活弹窗，实现破解
      8B4DF083C4106A10 -> 8B4DF083C410EB29 //跳过错误弹窗
    3.使用WinHEX等程序打开ActivationFx.dll，搜索并替换：
      CC833D14CD -> CC33C0C3CD

### fx-ES PLUS (2nd Edition)系列
包含以下14款模拟器（已去除2nd edition后缀）：

    fx-82/85/350ES PLUS, fx-570/991ES PLUS
    fx-300ES PLUS, fx-991ES PLUS C, fx-115ES PLUS
    fx-82/350LA PLUS, fx-570/991LA PLUS,
    fx-87DE PLUS
    fx-991ID PLUS
    fx-570VN PLUS
    fx-82AU PLUS II, fx-100AU PLUS
    fx-82ZA PLUS II, fx-991ZA PLUS II

该系列模拟器的破解方法与破解ClassWiz系列的方法相同。

### 其他资源
#### Fonts
收录的模拟器中除了ES系列外均具有 keylog 按键记录功能，若要使用这一功能需要安装模拟器对应的按键字体。ES PLUS（包括2nd Edition）系列需安装ES03，ES04字体，
ClassWiz系列的标准字体为ClassWiz.ttf，一些特殊型号的按键做了本土化，需要安装另外带有后缀的ClassWiz字体，即ClassWiz CE/DE/Fr/RS.ttf。

除此以外还收录了两款第三方制作的计算器屏显字体，安装后即可显示如同计算器屏幕上的像素字体。
ESPScreenLarge.ttf由[dingyuang](https://tieba.baidu.com/p/2298016562 'dingyuang')基于
ES PLUS系列的屏幕字体制作；CASIO\_Classwiz\_Display-Regular-1.001.otf由[-脱碳甲醛-](https://tieba.baidu.com/p/6807924855 '-脱碳甲醛-')基于
ClassWiz系列（fx-991CN X）的屏幕字体制作，user202729也提供了一部分素材。
#### DLL
部分系统在运行模拟器时会出现DLL文件丢失的提示，只需要将提示丢失的对应DLL文件复制到与模拟器同一目录下再运行即可解决。
