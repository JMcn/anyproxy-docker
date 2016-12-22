# Anyproxy-docker

Docker for [Anyporxy](https://github.com/alibaba/anyproxy), A fully configurable proxy in NodeJS, which can handle HTTPS requests perfectly.

# RUN

```
docker run -d --name anyproxy -p "8001:8001" -p "8002:8002" -v $(pwd):/anyproxy jmcn/anyproxy-docker
```

and open Web UI http://127.0.0.1:8002/

log path is /anyproxy
