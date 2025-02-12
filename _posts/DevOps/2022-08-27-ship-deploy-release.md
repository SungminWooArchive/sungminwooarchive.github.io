---
layout: single

title:  "\\[DevOps\\] Ship, Deploy, Release"
excerpt: ""

categories: 
    - Linux
tags: [linux, SE, apt]

toc: true
author_profile: false
sidebar:
    nav: "docs"

date: 2022-08-27
last_modified_at: 2022-08-27
---

### Shipping

배송은 빌드, 테스트, 릴리즈 및 배포까지 네 가지 개별 프로세스가 묶인 통합 프로세스를 일컫는다.

### Release

릴리즈는 패키지화되어 배포할 준비가 된 제품의 스냅샷

이런 스냅샷은 태깅될 수 있고 버저닝 되어 관리된다.

모든 릴리즈들이 배포되지는 않는다. 즉, 릴리즈 하는 목적은 내부 테스트, 특정 기능들의 버저닝 등등,

배포 외의 이유로도 진행할 수 있다.

### Deploy

배포는 프로덕션 인프라(클라우드 등)에 릴리즈(여기서 릴리즈는 명사)를 적용하는 것을 말한다.

### Rollback

롤백은 이전에 릴리즈로 돌리는 것이다.

롤백 역시 배포의 일종이다.

[Ship, Deploy, Release 개념 정리](https://brunch.co.kr/@thesorauniverse/4)