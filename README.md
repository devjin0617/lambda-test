# lambda-test

AWS Lambda 배포를 위한 npm module을 global로 설치
```
$ sudo npm install -g serverless
```

프로젝트 폴더로 이동하여 예제 템플릿으로 시작
```
$ serverless create --template hello-world
```

AWS 키 설정
> AWS 키 발급방법은: http://bit.ly/aws-creds-setup>
```
$ aws configure
```

AWS Lambda 배포
```
$ serverless deploy
```