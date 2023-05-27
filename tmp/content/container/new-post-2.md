---
title: "POST2"
date: 2023-05-24
menu:
  main:
    parent: "menu.container" 
    weight: 2   
---


# CONTAINER 명령어
- docker run: 컨테이너 생성과 실행을 위해 사용되는 명령어   
-> 예시: docker run [옵션] 이미지명 [명령어]

- docker ps: 현재 실행 중인 컨테이너 목록 보기   
-> 예시: docker ps [옵션]

- docker stop: 실행 중인 컨테이너를 정지   
-> 예시: docker stop 컨테이너ID

- docker start: 정지된 컨테이너를 시작    
-> 예시: docker start 컨테이너ID

- docker restart: 실행 중인 컨테이너를 재시작   
-> 예시: docker restart 컨테이너ID

- docker rm: 컨테이너를 삭제   
-> 예시: docker rm [옵션] 컨테이너ID

- docker images: 사용 가능한 도커 이미지 목록을 표시   
-> 예시: docker images [옵션]

- docker pull: 도커 이미지를 다운로드   
-> 예시: docker pull 이미지명

- docker exec: 실행 중인 컨테이너 내부에서 명령어를 실행   
-> 예시: docker exec [옵션] 컨테이너ID 명령어

- docker logs: 컨테이너의 로그를 확인   
-> 예시: docker logs [옵션] 컨테이너ID

- docker build: Dockerfile을 기반으로 도커 이미지를 빌드   
-> 예시: docker build [옵션] 경로

- docker network: 도커 네트워크를 관리, 컨테이너 간 통신을 제어하고 네트워크 설정을 구성하는 데 사용   
-> 예시: docker network [옵션] [명령어]

- docker volume: 도커 볼륨을 관리합니다. 데이터의 영구 저장을 위해 사용   
-> 예시: docker volume [옵션] [명령어]

- docker inspect: 도커 컨테이너, 이미지, 네트워크 등의 세부 정보를 확인   
-> 예시: docker inspect [옵션] 이름 또는 식별자

- docker-compose: 멀티 컨테이너 애플리케이션을 정의하고 실행하기 위한 도구, YAML 파일을 사용하여 여러 컨테이너를 설정하고 관리   
-> 예시: docker-compose [옵션] [명령어]

- docker save: 도커 이미지를 아카이브 파일로 저장   
-> 예시: docker save [옵션] 이미지명

- docker load: 아카이브 파일에서 도커 이미지를 로드   
-> 예시: docker load [옵션] 파일명

- docker commit: 실행 중인 컨테이너에서 변경 사항을 기반으로 새로운 이미지를 생성   
-> 예시: docker commit [옵션] 컨테이너ID [이미지명]

- docker stats: 실행 중인 컨테이너의 CPU, 메모리, 네트워크 등의 성능 및 리소스 사용량을 모니터링   
-> 예시: docker stats [옵션] [컨테이너ID]

- docker prune: 사용하지 않는 컨테이너, 이미지, 네트워크, 볼륨 등을 정리   
-> 예시: docker prune [옵션]
