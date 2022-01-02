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
# 연관 프로젝트 (tag:regacy/v1.0)가 모두 실행 중이어야 함
# 각 API가 실행 중이지 않을 경우 WEBAPP은 정상적으로 실행되지만 API server error 메세지를 테이블에 리턴
# nodejs 설치 필요
$ node -v
v16.13.1
$ npm -v
8.1.2

```

### 소스 코드 다운로드
```shell
[~]$ git clone https://github.com/daintree-henry/msa-sample-officeboard-webapp.git
[~]$ cd samplemsa-officeboard-webapp
[~/samplemsa-officeboard-webapp]$ tree
.
|-- README_en.md
|-- README_kr.md
|-- app.js
|-- images
|-- package-lock.json
|-- package.json
|-- public
|   `-- stylesheets
|       |-- main.css
|       `-- table.css
|-- routes
|   `-- index.js
`-- views
    |-- error.ejs
    `-- index.ejs


```

### 패키징
```shell
[~/samplemsa-officeboard-webapp]$ npm install
```

### 실행
```shell
[~/samplemsa-officeboard-webapp]$ npm start
```

### 테스트
브라우저에서 http://localhost:3000/webapp 접속

1. 각 API 서버가 실행 중인 경우
![](images/architecture.png)  

2. WEBAPP 만 실행할 경우
![](images/dashboard.png)  
   