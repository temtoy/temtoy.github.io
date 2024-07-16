---
layout: post
title: '"GCP Cloud Identity 설정"'
date: 2024-07-17 00:30:00 +0900
categories: GCP
---
# GCP Cloud Identity 설정 가이드

Google Cloud Platform을 개인 학습 목적이 아닌 작은 프로젝트 용도로 가지고 있는 도메인에 연결하려면 처음 마주하는게 Cloud Identity일 것이다.

처음 Google Account로 GCP Console에 접근하게 되면 Welcome 화면과 서비스 동의 화면이 나온다. 
![[Pasted image 20240717002908.png]]
이렇게 $300까지 크레딧을 받고 시작한 GCP를 잘 사용하다, 기능적 제한 또는 스케일 아웃을 고려하며 보유한 도메인을 연결하려고 한다면 Cloud Identity 설정을 만나게 된다.
