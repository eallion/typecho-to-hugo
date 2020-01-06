# typecho-to-hugo

通过 PHP 将博客从 typecho 转到 hugo ，感谢 [linx](https://llinx.me/post/typecho%E8%BF%81%E7%A7%BB%E5%88%B0hugo/) 提供大部分代码

将以上代码保存为convert.php, 放置到网站目录下，修改其中的mysql账号密码，即可导出hugo所需要的格式了。

如果有部分文章没有正常slug的那只能麻烦点手动修改文件名为文章名了，当然也可以再写个脚本，不过我文章不多, 就累点累点了，

注意：文件名中可以包含中文，也可以有括号 空格什么的，但有些字符应该手动把他修改掉 eg. # % @ 类似的这种本身就被用于URL的字符。
