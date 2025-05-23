# 🎯 HOBBYNEST: 취미 교환 플랫폼

곽곽이의열차분리 팀 - 2025-1 데이터베이스 팀프로젝트  
소프트웨어학과 202322051 곽민서, 202322094 이수연

## 📌 프로젝트 개요

**취미 교환 플랫폼(HobbyNEST)**은 내 취미가 머무를 수 있는 공간(둥지)을 찾고, 나와 어울리는 사람도 만나는 곳이라는 뜻으로 서로 다른 취미를 가진 사용자들이 자신의 취미를 다른 사람과 ‘교환’하고 함께 활동을 체험할 수 있도록 지원하는 서비스입니다. 예를 들어, 요리를 좋아하는 사용자는 사진 촬영에 관심 있는 사용자와 서로의 취미를 체험하며 기술을 공유할 수 있습니다.

이 플랫폼은 사용자-취미 간의 다대다 관계를 중심으로, 취미 수준, 교환 요청, 피드백, 추천 시스템 등을 포함한 데이터베이스 기반의 기능을 제공합니다. 외부 데이터셋(Kaggle의 취미 목록 데이터 등)을 활용하여 실제와 유사한 데이터를 기반으로 서비스를 구축하며, PostgreSQL과 Python을 사용하여 프로토타입을 구현합니다.

- 사용자-취미 간 **다대다 관계 모델링**
- **설문 기반 추천 시스템**
- **하비어 매칭**, **공간 안내**, **인기 취미 랭킹**
- **PostgreSQL + Python + Django** 기반
- Kaggle 등 **외부 데이터셋 활용**

## 🧩 주요 기능

### 1. 설문 기반 취미 추천 & 필터링 조회

- 활동 유형, 난이도, 계절, 비용 등 다양한 조건 기반 취미 탐색
- 설문 응답 기반 성향 분석으로 추천 점수 높은 취미 제안
- 점수순 정렬된 추천 결과 제공

### 2. 하비어(Hobbyer) 매칭 서비스

- 동일한 취미를 가진 사용자끼리 연결
- 지역, 실력 수준, 나이 필터 적용 가능
- '함께 활동할 취미 친구' 찾기에 초점

### 3. 인기 취미 랭킹

- 전체 사용자 데이터 기반으로 취미 랭킹 제공
- 등록 수 기반의 인기 취미 확인
- 실시간/주간/월간 랭킹 지원

### 4. 취미 활동 공간 안내

- 서울 내 공공 문화 공간과 연계
- 취미별 적합한 공간 추천
- 시설 위치, 유형, 지역 정보 제공

## 사용자 인터랙션 시나리오

![Image](https://github.com/user-attachments/assets/626514e9-a121-4a30-ace1-b53a801f1cd0)

## 서비스 아키텍처

![Image](https://github.com/user-attachments/assets/171ab6ba-8bfb-4760-ae18-fb523a395c5a)

## 🧪 개발 환경

- **DBMS**: PostgreSQL
- **언어**: Python
- **웹 프레임워크**: Django
- **IDE**: Cursor
- **데이터**: Kaggle 및 공공데이터포털
- **LLM**: ChatGPT 활용
