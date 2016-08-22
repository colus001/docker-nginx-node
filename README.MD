### 이 프로젝트는

Docker 를 사용하여 Nginx 로 Node.js Applciation 을 서빙하기 위한 샘플 어플리케이션

http://seokjun.kr/docker-nginx-node

### 앱 실행하기

1. 디팬던시 설치

  ```
  $ npm install
  ```

1. 실행

  ```
  $ npm start
  ```

### Dockerization

1. 이미지 생성

  ```
  $ docker build -t docker-nginx-node .
  ```

1. 이미지 실행

  ```
  $ docker run --name docker-nginx-node-instance docker-nginx-node
  ```

1. docker-compose

  ```
  $ docker compose up
  ```
