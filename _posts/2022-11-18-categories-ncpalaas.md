---
title: "[Day10] 하이퍼바이저(hypervisor) 알아보기"
excerpt: "하이퍼바이저 개념과 유형"

categories:
  - Naver Cloud Camp
tags:
  - [tag1, tag2]

permalink: /naver-cloud-camp/ncpalaas

toc: true
toc_sticky: true

date: 2022-11-18
last_modified_at: 2022-11-18
---

## 🦥 하이퍼바이저 *HyperVisor*

## 개념
   - 호스트 컴퓨터에서 다수의 운영 체제(operating system)를 동시에 실행하기 위한 논리적 플랫폼(platform)을 말한다. 가상화 머신 모니터 또는 가상화 머신 매니저(영어: virtual machine monitor 또는 virtual machine manager, 줄여서 VMM)라고도 부른다.

## 유형

### 타입1. *native* 또는 *bare-metal*
   - 운영 체제가 프로그램을 제어하듯이 하이퍼바이저가 해당 하드웨어에서 직접 실행되며 게스트 운영 체제는 하드웨어 위에서 2번째 수준으로 실행된다.

### 타입2. *hosted*
   - 하이퍼바이저는 일반 프로그램과 같이 호스트 운영 체제에서 실행되며 VM 내부에서 동작되는 게스트 운영 체제는 하드웨어에서 3번째 수준으로 실행된다.

  ![hyper](https://user-images.githubusercontent.com/118426681/203059856-0991d463-3740-49f7-ac8e-aaa071f4cf51.png)

  
