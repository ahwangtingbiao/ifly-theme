# 讯飞输入法最新构架模板
####导语
>  本代码几乎包含了[讯飞输入法](http://www.xunfei.cn)皮肤所有结构及配置方法，供那些喜欢折腾的童鞋们准备。如有问题请大家关注我微博[http://weibo.com/522239219](http://weibo.com/522239219)留言。

##皮肤结构介绍

###preview.jpg
> 讯飞输入法本地皮肤预览图

###info.ini
> 讯飞输入法皮肤基本信息配置文件
	#注意文件为utf-8格式
	[THEME_INFO]
	PLATFORM=android
	#==基础配置==
	#皮肤名称,建议8个汉字以内
	NAME=精细化适配模板
	#皮肤作者
	AUTHOR=iFlytek
	#皮肤设计适配分辨率
	RESOLUTION=1920x1080
	#唯一标识,生成网址：https://www.famkruithof.net/uuid/uuidgen
	ID=00000000-0000-0000-0000-000000000001
	#皮肤描述
	DESCRIPTION=精细化常用适配模板。

	#==进阶配置==
	#皮肤版本,大于9.00小于10.00,皮肤升级时使用
	VERSION=9.01
	#是否支持自定义工具栏：1或-1
	CUSTOM_CAND_SUPPORT=1
	#使用默认皮肤偏移量：1或0
	DEFAULT_OFFSET_SUPPORT=0
	#本地预览图
	Preview_Image=preview.jpg
	#键盘不透明度0-255
	THEME_ALPHA=255

	#以下内容请勿修改
	Protocol_Version=1.0
	Tone=1