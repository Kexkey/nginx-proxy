# https://github.com/jmparra/nginx-proxy

dockergen: docker-gen -watch -notify "nginx -s reload" /app/nginx.tmpl /etc/nginx/conf.d/default.conf
dockergen: docker-gen -watch -notify "nginx -s reload" /app/nginx.tcp.tmpl /etc/nginx/conf.d/tcp/default.conf
nginx: nginx
