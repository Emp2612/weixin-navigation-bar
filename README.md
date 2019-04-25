weixin-navigation-bar
因为小程序原生导航栏的一些限制，比如：不能设置字体大小，ios标题居中而安卓居左，从非首页启动小程序返回首页菜单不明显，屏幕空间不能最大化使用。因此微信开放了小程序自定义导航栏，允许用户最大化的使用屏幕空间。但是自定导航栏不支持只指定某些页面使用，而是全局的，所以也带来了一些适配问题。

本导航栏组件支持
可根据手机状态栏高度适配。
可自定义设置包括字体颜色、字体大小、背景颜色、无标题、导航栏是否置顶。
可自动识别是否首页launch。
组件自定义属性说明
属性	说明	类型	默认值
title	标题	String	none
color	标题字体颜色	String	#000000
fontSize	导航栏字体大小，单位rpx、px	String	40rpx
background	导航栏背景颜色	String	#ffffff
placeholderBg	导航栏占位栏背景色	String	transparent
back	是否显示导航栏返回按钮	Boolean	false
fixed	导航栏是否fixed定位置顶
使用说明
使用前需要了解小程序自定义组件和自定义导航栏。 app.json配置以下属性

"window":{
    "navigationStyle": "custom"
  }


github地址：



