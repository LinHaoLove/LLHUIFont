# LLHUIFont
为 app 添加第三方字体


1,下载所需要的字体文件包 举个栗子: LLHFont.ttf

2, 将字体文件包拖进自己的项目. Add fileS to @"LLHUIFont.xcodeproj"

3, 打开 Info.plist 文件在 Information Property List 下 Add Row,key是: Fonts provided by application,Type 是 Array,
	 在此之下, Add row, 直接在 value 下天写字体文件包全称:LLHFont.ttf
	 
	 ![image](https://github.com/LinHaoLove/LLHUIFont/blob/master/3.png)
	 
	 
4,找到字体名称(不同于字体文件包名称)

	方法1:用 Mac 的 Font Book 打开字体文件包.弹出框顶部显示的就是字体的名称.
	方法2:在 Xcode 中打印,慢慢找吧.
	![image](https://github.com/LinHaoLove/LLHUIFont/blob/master/2.png)
	
		
5,如果上述步骤确定无误,但未显示效果.

        打开项目 Targets  中Build Phases->Copy Bundle Resources 中是否显示字体文件包,如果没有点击+ 添加.
        ![image](https://github.com/LinHaoLove/LLHUIFont/blob/master/1.png)
        
        	 
6, 效果(楷体的一种)
		
	![image](https://github.com/LinHaoLove/LLHUIFont/blob/master/5.png)

