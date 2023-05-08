# msa-spring-config-files
spring boot config files with msa spring boot

### Spring Cloud Config 서버의 설정 파일
configServer(외부시스템)를 띄우고 MSA 서비스에 사용되는 Config 정보들을 Git Repostory에 저장하고 ConfigServer는 Git Repository에서 설정 정보를 읽는다.ㅇ
모든 마이크로 서비스는 다시 빌드하지 않고 설정 파일을 변경한 뒤 Spring cloud bus 이용하여 변경 사항을 연결 된 서비스에 전달한다

### config(yml)
- application.yml : 마이크로 유저 서비스 설정 파일 
- ecommerce-dev.yml : 마이크로 서비스의 apigateway 서비스 개발환경 설정 파일 
- ecommerce-prod.yml : 마이크로 서비스의 apigateway 서비스 운영환경 설정 파일 
- ecommerce.yml : 마이크로 서비스의 apigateway 서비스 설정 파일 
- user-service.yml : 마이크로 유저 서비스 설정 파일 
