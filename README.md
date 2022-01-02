## MSA-SAMPLE-OFFICEBOARD-Webapp
각 API의 정보를 UI로 나타내는 WEBAPP입니다. Node.js 서버 실행이 필요하며 두 개의 REST API의 정보를 대시보드에 호출합니다.

![](images/architecture.png)  
![](images/dashboard.png)  

### 연관 프로젝트
[msa-sample-officeboard-employeeapi](https://github.com/daintree-henry/msa-sample-officeboard-employeeapi)  
[msa-sample-officeboard-itemapi](https://github.com/daintree-henry/msa-sample-officeboard-itemapi)  

### API 호출 
웹 브라우저에서 http://localhost:3000/webapp 접속

## Initial Version 
일반 서버에서 테스트하기 위한 소스코드

### 사전 준비
```shell
#nodejs 설치 필요
$ node -v
v12.22.8
$ npm -v
6.14.15

```

### 소스 코드 다운로드
```shell
[~]$ git clone https://github.com/daintree-henry/msa-sample-officeboard-webapp.git
```

### 패키징
```shell
[~]$ cd samplemsa-officeboard-webapp
[~/samplemsa-officeboard-webapp]$ npm install
```

### 실행
```shell
[~/samplemsa-officeboard-webapp]$ npm start
```