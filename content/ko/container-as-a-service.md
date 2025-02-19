---
title: 서비스형 컨테이너 (Containers as a Service)
status: Completed
category: 기술
tags: ["플랫폼", "", ""]
---

## 개념

서비스형 컨테이너(CaaS)는 [컨테이너](/ko/container/) 기반 [추상화](/ko/abstraction/)를 통해
앱을 관리하고 배포하는 데 유용한 클라우드 서비스이다.
이 서비스는 온프레미스 또는 클라우드에 배포될 수 있다.

서비스형 컨테이너 공급자는 컨테이너가 배포 및 관리되는 주요 IT 기능을
자동화하는 프레임워크 또는 오케스트레이션 플랫폼을 제공한다.
이는 개발자가 안전하고 [확장 가능한](/ko/scalability/) 컨테이너화된 앱을 빌드하는 데 도움을 준다.
사용자는 필요한 리소스(스케줄링 기능, 로드 밸런싱 등)만 구매하기 때문에,
금액을 절약하고 효율성을 높일 수 있다.
컨테이너는 어디서나 실행할 수 있는 [클라우드 네이티브 애플리케이션](/cloud-native-apps/)을 
빠르게 개발하고 전달할 수 있는 일관된 환경을 제공한다.

## 다루는 문제

CaaS가 없으면, 소프트웨어 개발 팀이 컨테이너가 실행되는 기본 인프라를
직접 배포, 관리 및 모니터링해야 한다.

## 문제 해결 방식

컨테이너화된 애플리케이션을 CaaS 플랫폼에 배포할 때,
사용자는 로그 집계 및 모니터링 도구를 통해 시스템 성능에 대한 가시성을 얻는다.
CaaS에는 [오토스케일링](/ko/auto-scaling/) 및 오케스트레이션 관리를 위한 내장 기능도 포함되어 있다.
이를 통해 사용자들은 높은 가시성과 고가용성 [분산 시스템](/distributed-systems/)을 구축할 수 있다.
또한 CaaS는 신속한 배포를 가능하게 하여 개발 속도를 향상시킨다.
컨테이너는 일관된 배포 타겟을 보장하므로,
CaaS는 배포 관리에 필요한 [데브옵스](/ko/devops/) 리소스를 줄임으로써
엔지니어링 운영 비용을 절감하게 해 준다.
