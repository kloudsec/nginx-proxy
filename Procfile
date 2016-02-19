nginx: /opt/nginx/sbin/nginx
dockergen: docker-gen -watch -only-exposed -notify "/opt/nginx/sbin/nginx -s reload" /app/nginx.tmpl /opt/nginx/conf/conf.d/default.conf
