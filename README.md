# ueditor-for-emlog

#更新日志
2014-09-17 21:20:34 [ueditor for emlog 4.2]
* 支持emlog5.3.1
* 使用ueditor php utf-8 1.4.3
* pageBreakTag分隔线改为[break]摘要截断符

# 使用说明
由于emlog要修改自带的编辑器用插件的方式实现方法比较麻烦，这里采用替换覆盖方法的方法来实现。直接覆盖到emlog博客的根目录，覆盖掉admin中的部分文件。

# 卸载说明
使用emlog自带的文件替换掉修改列表修改的这几个文件，然后删掉ueditor（使用过ueditor内置的附件图片上传慎删）

# 修改列表
* admin目录下添加ueditor文件夹
* add_log.php 新建文章
* add_page.php 新建页面
* edit_log.php 修改文章
* edit_page.php 修改页面
* common.js

# 联系作者
* 你可以在[星之宇个人博客](http://www.myxzy.com)找到联系方式
* 作者博客该项目主页[点击这里](http://www.myxzy.com/ue4em.html)
