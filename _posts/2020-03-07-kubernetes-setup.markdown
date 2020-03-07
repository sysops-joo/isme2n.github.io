---
layout: post
title: 'Private 환경은 귀찮은게 많아;'
subtitle: 'Private 환경은 귀찮은게 많아;'
categories: kubernetes
tags: [ private, cloud, kubespray ]
comments: true
---

이것저것 테스트하다보니 약 2주 정도 걸렸습니다.

---
### DMZ
- haproxy

### Mgmt
- local repo, dns, squid

### Bootstrap 
- ansible, kubespray(v2.12.1), kubectl

### Kubernetes
- master 3ea
- worker 3ea

### Network
- 1Gb

### Image repo
- nexus


