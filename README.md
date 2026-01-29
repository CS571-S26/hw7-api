build
```bash
docker build . -t ctnelson1997/cs571-s26-hw7-api
docker push ctnelson1997/cs571-s26-hw7-api
```

run
```bash
docker pull ctnelson1997/cs571-s26-hw7-api
docker run --name=cs571_s26_hw7_api -d --restart=always -p 58107:58107 -v /cs571/s26/hw7:/cs571 ctnelson1997/cs571-s26-hw7-api
```
