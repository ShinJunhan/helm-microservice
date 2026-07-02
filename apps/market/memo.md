
```bash
docker build -t myoli999/market-app:1.0 .
docker push myoli999/market-app:1.0


# health 체크 기능 추가한 후에 이미지 다시 build 해서 push하기
docker build -t junhanshin/market-app:1.1 .
docker push junhanshin/market-app:1.1
```