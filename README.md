# wechat-auth
微信多域名授权API
可供免备案域名授权使用

# 使用说明
1.把index.php放入已填入微信公众号授权域名的域名的根目录中（任何二级目录都可以，无需再修改代码），比如：https://xulgr.com/index.php ；
2.再需要授权的其他域名的微信授权接口代码中，搜索 https://open.weixin.qq.com/connect/oauth2/authorize 这个链接，替换成上一步的域名的index.php所在目录即可。
