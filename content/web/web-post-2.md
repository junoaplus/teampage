---
title: "Web_Backend"
date: 2023-05-28
menu:
  main:
    parent: "menu.web" 
    identifier: "post8"
    title: "Post2"
    weight: 2      
---

# Web_Backend(server)

## Client & Server
  - 클라이언트 = 브라우저
  - tier = 서비스를 구성하는 로컬 컴퓨터의 개수
  1. 2-tier architecture   
      클라이언트는 브라우저를 통해 url과 연결된 DB에서 다음과 같은 항목을 가져온다.   
      + html
      + css
      + js
  2. 3-tier architecture   
      데이터 저장 및 관리 서버와 기존 비즈니스 로직 서버를 구분한다.
      + 예시 : MSA

## Java Springboot
요즘 jjeongee가 배우고 있는 백엔드 및 서버 언어이다.

springboot의 framework
- IoC container : 외부에서 생성한 객체를 각각 스프링컨테이너에 저장하여 불러와서 사용한다.
- 관심사 분리
  + Controller : 요청을 받고 서비스를 이용해서 응답 생성
  + Service : 전달받은 데이터를 트랜잭션 단위로 비즈니스 로직을 수행한다. repository를 이용해서 데이터를 다룸
  + Repository : DB에 직접 접근해서 데이터를 다룸
  + Domain : 각 요소들이 데이터를 전달하는 단위