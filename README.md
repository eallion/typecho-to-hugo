# typecho-to-hugo

通过 PHP 将博客从 typecho 转到 hugo ，感谢 [linx](https://llinx.me/post/typecho%E8%BF%81%E7%A7%BB%E5%88%B0hugo/) 提供大部分代码。

1. clone 或[下载](https://github.com/eallion/typecho-to-hugo/archive/master.zip)本 repo
2. 修改其中的 mysql 账号密码（第3行）
```
$db->connect('localhost','root','password','typecho');
```
3. 将 convert.php 上传到网站目录下
4. 通过浏览器访问`htttps://www.example.com/convert.php`即可导出 Hugo 所需要的格式了。

### Update
添加 slug 字段