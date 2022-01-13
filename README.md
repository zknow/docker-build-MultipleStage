# Docker Build SingleStage & MultipleStage

簡單的golang程式碼docker build出來的image卻動輒3、400M，紀錄一下使用Single Stage與Multiple Stage Build 的範例以及Image的容量差異

#### CMD

```sh
docker build -t zknow/go-app .
```

#### Single-Stage
![image](https://github.com/zknow/two-ways-docker-build/blob/master/single-stage/size.png)

#### Multi-Stage
![image](https://github.com/zknow/two-ways-docker-build/blob/master/multi-stage/size.png)



