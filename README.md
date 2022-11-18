# nginx for webdav

all modification under branches/stable-1.22 

## added patch to show dot file

[ref ticket](https://trac.nginx.org/nginx/ticket/557)

[file url: ngx_autoindex_show_dot_files.patch](https://trac.nginx.org/nginx/raw-attachment/ticket/557/ngx_autoindex_show_dot_files.patch)

related file:

`./src/http/modules/ngx_http_autoindex_module.c`

## put 3rd party module into folder for easier enable full functionality for webdav when building

[git repo](https://github.com/arut/nginx-dav-ext-module)

