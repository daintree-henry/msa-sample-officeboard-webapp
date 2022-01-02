## MSA-SAMPLE-OFFICEBOARD-Webapp
This APP is UI showing each API's data. You need to execute on a Node.js server. It requests two APIs and shows data returned on the dashboard.

![](images/architecture.png)  
![](images/dashboard.png)  

### Related Projects
[msa-sample-officeboard-employeeapi](https://github.com/daintree-henry/msa-sample-officeboard-employeeapi)  
[msa-sample-officeboard-itemapi](https://github.com/daintree-henry/msa-sample-officeboard-itemapi)  

### API Requests 
Typing http://localhost:3000/webapp on your web browser

## Initial Version 
This version is initial version for reguler server, not container.

### Dependencies
```shell
#You need to run related projects already (tag:regacy/v1.0)
#If these projects is not running, the WEBAPP runs but returns "API server error" messages. 
#You need to install nodejs
$ node -v
v16.13.1
$ npm -v
8.1.2

```

### Download the source code
```shell
[~]$ git clone https://github.com/daintree-henry/msa-sample-officeboard-webapp.git
```

### Packaging
```shell
[~]$ cd samplemsa-officeboard-webapp
[~/samplemsa-officeboard-webapp]$ npm install
```

### Run
```shell
[~/samplemsa-officeboard-webapp]$ npm start
```

### Test
Typing http://localhost:3000/webapp on your web browser

1. All API server is running

2. Only the WEEBAPP is running
   
