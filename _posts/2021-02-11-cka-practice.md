---
title: "CKA practice"
last_modified_at: 2021-02-11T16:22:00-00:00
categories:
  - Blog
tags:
  - practice
---

Daily note

- 20210203 -Scheduling 테스트 (~ Node affinity)
- 20210204 - Scheduling 테스트 (~ End)
- 

To study

- Resource monitoring (kubectl top pod/node)
- namespace로 network policy selector
- kubeadm

Memo

- Static pod구별법: 뒤에 노드명이 붙는다 ex. -controlplane, -node01
- Static pod yaml정의 위치는? kubelet을 ps로 확인 후 config세팅 확인
- Multiple scheduler배포하는것은 공부해야하는건가? 일단 kube-scheduler를 복사해서 하는건 연습에서 했음. scheduler-name을 설정해야함. 이상하게도 ""를 넣으면 제대로 답으로 인정안됨. 돌렸는데 Running상태에서 멈춰있음 추후 다시 풀어보기([https://kodekloud.com/courses/certified-kubernetes-administrator-with-practice-tests-labs/lectures/12038844](https://kodekloud.com/courses/certified-kubernetes-administrator-with-practice-tests-labs/lectures/12038844) 3번문제)