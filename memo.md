# step24_microservice_helm/memo.md

```bash
# chart 를 압축해서 docs/ 폴더 안에 저장하기
helm package . -d docs/

# index.yaml 파일을 docs/ 폴더 안에 자동 생성하기
helm repo index docs --url https://ShinJunhan.github.io/helm-microservice/

```