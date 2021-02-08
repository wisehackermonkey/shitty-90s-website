# shitty-90s-website
### recreation of a 90's era websites made for fun :)
```bash
by Oran C <Oranbusiness@gmail.com>
github.com/wisehackermonkey
20210207
```

![](2021-02-08-00-45-26.png)

# Deploy website
## how to build docker
```bash
docker build -t wisehackermonkey/shitty-90s-website:latest .
docker login
docker push wisehackermonkey/shitty-90s-website:latest
```

## run
```bash
docker-compose up -d
```