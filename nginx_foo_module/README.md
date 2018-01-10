# nginx fool module
参考：http://nginx.org/en/docs/dev/development_guide.html#core_modules

编译方法：
进入nginx源码目录执行：
`./configure --prefix=/usr/local/nginx --with-mail --with-mail_ssl_module --with-debug --add-module=/nginx_module_dir/nginx_foo_module`
