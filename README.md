![](http://upload-images.jianshu.io/upload_images/4043475-5538382cc638f16f.gif?imageMogr2/auto-orient/strip)


##1. 使用步骤：

####1. 在项目的 build.gradle 文件中添加

		allprojects {
			repositories {
				...
				maven { url 'https://jitpack.io' }
			}
		}

####2. 在 module 的 build.gradle 文件中添加依赖

		dependencies {
		        compile 'com.github.xiaweizi:XWZWebView:1.1.0'
		}

####3. 一步调用

		WebViewActivity.startUrl(context, url);
> 第一个参数就是上下文，第二个参数就是跳转的链接 `URL`

##2. 依赖库特点：

>1. 支持侧滑结束 WebViewActivity
>2. 支持缩放
>3. 设置缓存
>4. 进度显示
>5. 点击返回键回退到上个浏览记录
>
>等等...

![](https://jitpack.io/v/xiaweizi/XWZWebView.svg)
