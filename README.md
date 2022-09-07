# Unity单选框，复选框

#### 介绍
Unity单选框，复选框，可代替unity自带Toggle组件，自定义配置项多，操作简单
如有任何问题请加企鹅群：747648080

#### 软件架构
软件架构说明


#### 安装教程

1.  下载拖入工程中
2.  在要设置的按钮上添加Tab脚本
3.  根据添加后，Inspector上的提示，设置鼠标移入及点击时的设置

#### 使用说明

1.	TabTxt： 按钮下的text
2.  MultipleChoice:是否为复选框
3.  IsOn:当前是否为选中状态，手动勾选的话，初始化时为默认选中状态

鼠标移入状态设置
1.	IsHoverImgActive： 鼠标移入改变显示状态
2.	IsHoverTxtColor： 鼠标移入改变文字显示颜色	
3.	IsHoverImgColor： 鼠标移入改变图片显示颜色
	以上选中后根据提示设置相应内容即可

选中时状态设置
1.	IsOnImgActive：选中后改变图片显示状态
2.	IsOnTxtColor: 选中后改变文字显示颜色
3.	IsOnImgColor：选中后改变图片显示颜色
	以上选中后根据提示设置相应内容即可
	showPanel：为选中时需要显示的对象，通过setactive设置，可不设置

4.	Tabcontroller：父级控制器，可手动配置，如果没有手动配置，会默认在直接父级上创建
5.	TabName: 无实际作用，可给按钮设定标签名	

API
1.	TabClick（广播事件）：可获取当前点击的对象（类型：Tab），每次点击都能获取到
2.	TabClickFirstEffect（广播事件）：可获取当前点击的对象（类型：Tab），仅获取第一次
3.	text（属性）：可获取按钮下text的名称
4.	IsOn：设置显示状态，TabClick和TabClickFirstEffect可获取到点击事件
5.	IsOnWithOutEvent：仅改变状态，没有事件的触发


#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
