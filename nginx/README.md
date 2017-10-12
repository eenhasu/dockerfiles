# nginx

nginx sorce build with linux

## run

```
$ docker run -p 80:80 -v /data/nginx/sites:/usr/local/nginx/conf/sites -d cincrain/nginx:1.13.4
```

## volume

- /usr/local/nginx/conf/certs
  - ssl cert file
- /usr/local/nginx/conf/conf.d/*.conf
  - additional nginx configuration
- /usr/local/nginx/conf/sites
  - http configuration
- /usr/local/nginx/conf/streams
  - stream configuration
