
https://wiki.archlinux.org/index.php/Nginx

static files: https://docs.nginx.com/nginx/admin-guide/web-server/serving-static-content/

basic auth: https://docs.nginx.com/nginx/admin-guide/security-controls/configuring-http-basic-authentication/

Better passwords:

```sh
printf "${username}:`openssl passwd -apr1`\n" >> .htpasswd
```

Reverse proxy: http://nginx.org/en/docs/beginners_guide.html#proxy

SSL: https://wiki.archlinux.org/index.php/Certbot
