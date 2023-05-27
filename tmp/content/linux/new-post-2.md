---
title: "Post2"
date: 2023-05-22
menu:
  main:
    parent: "menu.linux" 
    identifier: "post6"
    title: "Post2"
    weight: 2      
---

Kernel 종류
Single-tasking and multi-tasking
• 싱글태스킹 : 한 번에 하나의 프로그램만 실행 가능

• 멀티태스킹 : 동시에 2개 이상의 프로그램을 실행 가능(time-sharing)

Single- and multi-user

• 단일사용자용(single-user) : 사용자 구별이 없음

• 다중사용자용(multi-user) : 사용자별 자원과 프로세스를 식별하여 여러 사용자들이 독립적으로 사용할 수 있도록 지원
단일형커널과 마이크로커널

• Monolithic Kernel : 모든 운영체제가 하나의 커널 공간에서 실행됨

• 통합되어 한 번에 실행되므로 더 빠르게 실행

• 모듈간 상호 작용이 직접 실행됨

• 구조가 단순함

• 전체 커널을 잘 만들어야 함

• Microkernel: 최소한의 운영체제 기능만을 커널에 구현하고 다른 기능들은 서버 형태로 제공

• 작고 독립적이어서 모듈간 영향을 많이 주지 않음

• 부분적으로 재 로드할 수 있고, 커널 전체를 재 컴파일 하지 않고 기능 추가 가능

• 실행에 부가 비용이 발생 -> 성능 문제 발생 가능


Linux Kernel 분류

Multi-tasking, Multi-user, 단일형커널
• Linux kernel은 기본적으로 Multi-tasking, Multi-user, 단일형커널
• 임베디드 OS의 경우 커널을 수정하여 Single-task나 Single-user용으로 사용하기도 함

