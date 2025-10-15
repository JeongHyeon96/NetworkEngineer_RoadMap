# KISTI + KREONET 환경을 고려한 네트워크 엔지니어 로드맵

## 핵심 포인트
**KISTI**는 국가 슈퍼컴퓨터, 연구데이터 허브, 국가연구망(KREONET)을 운영하는 핵심 기관입니다.  
**KREONET**은 국내 연구기관, 대학, 병원 등을 초고속 네트워크로 연결하는 L2/L3 백본 연구망이며, 해외 연구망(APAN, GEANT 등)과도 연동됩니다.

주요 특징:
- 대규모 백본 네트워크 운영 경험
- SDN, IPv6, 고속 전송(100G 이상), 멀티도메인 전송 기술 노출
- 클라우드·연구망 융합 환경 실험 가능
- 공공기관 및 연구기관 협업 경험

---

## 네트워크 엔지니어 로드뷰 (신입 기준)

### 1년 차: 연구망 구조 이해 + 운영 기초 익히기
**기술 목표**
- 네트워크 기초 (TCP/IP, OSI 7계층, 서브넷 계산 등)
- 리눅스, Cisco 장비 CLI 완숙도 향상
   - Cent OS 8: 이것이 리눅스다(https://www.youtube.com/watch?v=ovrU9K3jfJs&list=PLVsNizTWUw7EJ9z-LW3lv3VC-6HI9I3hN）
   - Rocky Linux: 이것이 리눅스다(https://www.youtube.com/watch?v=7KR8ol-Z8h8&list=PLVsNizTWUw7FqN2gq79Cb3R6qkS7mqOJk)
- Python 기본 문법 및 네트워크 자동화 툴(Netmiko, NAPALM) 학습
   - Python 강의: 조코딩 (https://www.youtube.com/watch?v=7ttbyGI5igA&list=PLU9-uwewPMe05-khW3YcDEaHMk_qA-7lI)
- KREONET 백본 구조 및 트래픽 흐름, 장비 구성 학습

**실무 경험**
- 라우터/스위치 설정 변경, 장애 처리 보조
- NetFlow, SNMP, 로그 모니터링 분석
- 연구망 트래픽 흐름 문서화 및 구성도 작성

**자기 개발**
- 네트워크 기초 실습: VPC, Subnet, Routing Table, IGW 등 (GNS3, Cisco Packet Tracer, 실제 장비)
- Github 정리 습관화

---

### 3년 차: 기초 기반 + AI 활용 기초 
**기술 목표**
- Python + Ansible 자동화 실무 적용 및 AI 연계 자동화 기초 학습(Python + OpenAI API로 간단한 네트워크 설정 툴 제작)
- 네트워크 로그 분석 자동화에 AI 모델 활용 시도 (LLM or ML)
- SDN / Segment Routing 개념 학습 및 PoC 실습

**실무 경험**
- 기관 간 BGP 구성, 멀티홈 라우팅 경험
- 네트워크 구성 자동화에 LLM 활용 실험 (예: "자동 BGP 설정 템플릿 생성기")
- 자동화 스크립트로 설정 백업, 장비 점검 등 운영 효율화
- 로그 데이터를 수집/분석하는 간단한 AI 로깅 대시보드 설계 PoC

---

### 5년 차: 클라우드 네트워크 전문가로 전환
**기술 목표**
- AWS Advanced Networking + Terraform 숙련 + AWS AI 서비스 연계
- SDN, ONOS/ODL 실습 적용
- 클라우드 보안 정책 최적화에 AI Rule Engine 적용 경험
- LLM을 이용한 네트워크 문서 자동화 / 설계 시뮬레이션 도구 개발

**실무 경험**
- 연구망과 클라우드 연동 인프라 구축 주도
- 멀티클라우드 환경에서의 AI 기반 이상 탐지/알람 시스템 설계
- AI 기반 네트워크 트래픽 예측/경보 시스템 구축

---

### 요약
- 1.Python + 네트워크 엔지니어링 + AI 기초 프로젝트 수행(예: 네트워크 구성 파일 요약기, 설정 자동 생성기 등)

- 2.LLM API (OpenAI, Anthropic 등) 활용한 실습 경험(예: ChatGPT API + CLI로 간단한 자동화 도구 만들기)



# ![네트워크 엔지니어 로드맵 참고사진](NetengRoadmap.png)
