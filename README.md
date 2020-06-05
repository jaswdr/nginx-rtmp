# NGINX with RTMP for livestreaming

### Getting started

```
$ docker-compose up -d
```

Open OBS and start streaming to `rtmp://localhost/live` with streaming key with the name of your streaming, like `testing`

Access https://players.akamai.com/players/hlsjs and use http://localhost:8080/testing as input stream URL.

That's it, you are live!

### See more

[Nginx RTMP mod](https://github.com/arut/nginx-rtmp-module)
