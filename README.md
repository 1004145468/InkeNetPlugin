## 1. 插件功能介绍：
> 根据网络请求Key-value对中的Key生成网络请求代码

## 2. 插件内容输入
>* 网络请求地址
>* 请求参数,类型，参数介绍（用于生成请求JavaBean）
>* 响应json字符串( 用于生成响应JavaBean)
>* 请求方式选择（GET / POST）

## 3. 生成代码
>* 生成网络请求类
>* 生成网络请求方法,供外部直接调用
>* 生成网络响应类

## 4. 友好使用交互
>* 自动打开代码好的文件，以供开发者定位文件进行代码调整

## 5.目的
>* 本项目给插件学习者提供参考，学习后，能轻松进行插件开发。

## 6.进阶使用
>* 插件开发支持模板化开发： PsiClass clazz = JavaDirectoryService.getInstance().createClass(directory, className, templateName)

## 7. 效果截图
![效果为:demoshow.gif文件](https://github.com/1004145468/InkeNetPlugin/blob/master/demoshow.gif)
