# 🏠 Jeonse-SoundMap: 안전한 주거지 탐색 서비스

> 👨🏻‍💻 **국토교통부 공공데이터 활용 경진대회 출전작**

---

## 📌 서비스 한 줄 요약

**지역별 전세사기 피해와 소음 민원 데이터를 지도에 시각화하여, 안전한 주거지 선택을 돕는 웹 서비스**

---
## 🧭 프로젝트 개요

2025 국토교통부 공공데이터 활용 공모전에 출전한 본 프로젝트는,
**전세사기 피해 정보와 생활 소음 데이터를 지도 기반으로 시각화**하여 사용자에게 **보다 안전하고 쾌적한 주거 환경을 선택할 수 있도록 돕는 서비스**입니다.

---

## 🛠 기술 스택

* **Backend**: Spring Boot
* **Frontend**: Vite + React
* **Database**: PostgreSQL
* **DevOps**: Docker, Docker Compose 을 활용해 개발 / 구도 / 실행 가능

---

## 💡 서비스 기획 배경

전세사기와 소음 민원은 주거지 선택 시 중요한 요소지만, 일반 사용자에게 직관적으로 제공되는 정보는 부족합니다.
이에 따라 **서울 자치구별 전세사기 피해 주택 수와 소음 민원 통계를 통합 시각화**하여,
**지도 기반으로 누구나 쉽게 안전성을 판단할 수 있는 서비스**를 개발하게 되었습니다.

---

## 🔗 사용 데이터 출처

### [소음 민원 통계] https://www.noiseinfo.or.kr/noise/statistics.do

### [전세사기 피해 주택 수] https://www.data.go.kr/data/15139145/fileData.do

---

## 🎯 MVP 메인 타깃

> "서울/수도권에서 첫 독립을 준비 중인 20\~30대 사회초년생 및 대학생"

* 원룸, 투룸, 전세/반전세 매물을 탐색 중
* 부동산 경험 부족으로 사기 위험에 노출
* 지리적 정보 + 안전 + 생활환경 등 종합적 판단 필요
* 기존 플랫폼(직방/네이버 부동산)에서는 사기/소음 정보가 부족함

✔ **우리의 해결책**

* 전세사기 피해 데이터 + 소음 민원 데이터를 시각화
* 한 화면에서 비교 가능한 **지도 기반 비교 UI 제공**

---

## 🔁  서비스 사용 전 후 비교
| 항목 | 사용 이전 | 사용 이후 |
| --- | --- | --- |
| 정보 접근성 | 공공데이터 직접 탐색 필요 | 한 화면에서 데이터 통합 확인 |
| 안전성 판단 기준 |	경험/추측에 의존 | 데이터 기반 판단 가능 |
| 의사결정 시핵시간 | 정보 파편화로 시간 소요 | 시각화로 빠르고 직관적 판단 |
| 사기·소음 피해 | 사기/소음 피해 위험 미인지| 고위험 지역 사전 회피 가능 |

---

## ✨ 핵심 기능 요약
* **지도 기반 시각화**: 자치구별 전세사기 피해 수 + 소음 민원 통계를 색상/툴팁 기반으로 표시
* **지역 필터링 기능**: 원하는 자치구 선택, 단일 데이터(전세사기/소음) 필터링
* **위험도 레벨링**: 색상 단계로 위험도 표현 

---

## 🎯 기대 효과

* **정보 격차 해소**: 사회초년생이 객관적 데이터를 통해 안전하게 집 선택 가능
* **피해 예방**: 사기/소음 고위험 지역 선별 → 위험 회피 가능
* **의사결정 효율화**: 시각적 정보 제공 → 탐색 시간 절감
* **공공데이터 활용 사례 확장**: 실생활에 적용 가능한 성공적인 데이터 활용 모델

---

## 팀원 소개
## 👥 팀원 소개

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Kimgyuilli">
        <img src="https://avatars.githubusercontent.com/Kimgyuilli" width="100px;" alt=""/>
    </a>
        <br /><sub><b>👨🏻‍💻김규일</b></sub><br/>
        <sub>PM</sub><br/>
        <sub>소음 데이터 담당</sub>
    </td>
    <td align="center">
      <a href="https://github.com/goodjunseon">
        <img src="https://avatars.githubusercontent.com/goodjunseon" width="100px;" alt=""/>
    </a>
        <br /><sub><b>👨🏻‍💻박준선</b></sub><br/>
        <sub>Backend Developer</sub><br/>
        <sub>회원 기능 담당</sub>
    </td>
    <td align="center">
      <a href="https://github.com/zldzldzz">
        <img src="https://avatars.githubusercontent.com/zldzldzz" width="100px;" alt=""/>
    </a>
        <br /><sub><b>👨🏻‍💻이원진</b></sub><br/>
        <sub>Backend Developer</sub><br/>
        <sub>전세 사기 데이터 담당</sub>
    </td>
  </tr>
</table>

##  🎥 실행 화면
<h3><details>
<summary> 👤  회원가입 </summary>

https://github.com/user-attachments/assets/d2ae88de-db42-4da7-8bf8-0008a2000349

</details></h3>

<h3><details>
<summary> 🔐 로그인 및 회원정보 수정  </summary>

https://github.com/user-attachments/assets/4c87d07e-5230-406b-b3ba-5e59f056ca7f

</details></h3>

<h3><details>
<summary> 🚨 전세사기 지도 </summary>

https://github.com/user-attachments/assets/49689f4b-b641-4824-b665-a33837b5c083

</details></h3>

<h3><details>
<summary> 🔊 소음 지도</summary>
  

https://github.com/user-attachments/assets/da58f7f9-7264-4ebb-8a2e-28f58e2ad2ef

</details></h3>

# ⚙️ 시스템 아키텍처
![image](https://github.com/user-attachments/assets/d519f61e-1243-492b-9163-61a27f2903c0)

## 📦  프로젝트 기술 스택
| 구분                    | 기술 스택                                                |
| --------------------- | ---------------------------------------------------- |
| **Frontend**          | React (Vite) + TypeScript, Axios, Recharts           |
| **Backend**           | Spring Boot, Spring Security, OAuth2, JWT            |
| **Database**          | PostgreSQL                                           |
| **Cache / Token 저장소** | Redis                                                |
| **인증 및 인가**           | JWT Access & Refresh Token, OAuth2 (카카오 로그인)         |
| **Infra / DevOps**    | Docker, Docker Compose, EC2 (Ubuntu), GitHub Actions |
| **배포**                | Nginx, GitHub Actions + Docker Hub + EC2             |
| **버전 관리**             | Git + GitHub                                         |
| **기타**                | REST API, .env 환경변수 설정, Git 커밋 컨벤션 적용           |

## 📐  프로젝트 설계
### 🔄  API 흐름 구조
* 클라이언트 → API 서버(Spring Boot) → JWT 발급 / Redis 저장
* 메인페이지 및 마이페이지 API 요청에 Access Token을 헤더에 포함
* 지도 API는 로그인 후 이동한 화면에서 접근
* Refresh Token은 Redis에서 유효성 검사 후 Access Token 재발급

### 🗃  데이터 베이스 ERD
- 소음지도

| Entity           | 필드명       | 타입                  | 제약 조건 / 관계          |
| ---------------- | --------- | ------------------- | ------------------- |
| **NoiseStation(1)** | id        | Long                | PK, Auto Increment  |
|                  | location  | String              | 측정소 이름/위치           |
|                  | latitude  | Double              | 위도                  |
|                  | longitude | Double              | 경도                  |
| **NoiseReading(N)** | id | Long | PK, Auto Increment |
|  |decibel | Double | 데시벨 측정값 |
|  |timestamp | LocalDateTime | 측정 시간 |
| | station | NoiseStation | FK, ManyToOne |

- 전세사기 지도

| Entity           | 필드명        | 타입            | 제약 조건 / 관계         |
| ---------------- | ---------- | ------------- | ------------------ |
| **FraudReading** | id         | Long          | PK, Auto Increment |
|                  | district   | String        | 자치구 이름 (예: 강남구)    |
|                  | fraudCount | Integer       | 전세사기 발생 건수         |
|                  | timestamp  | LocalDateTime | 수집 시간 또는 기준 일자     |



## 🧾  커밋 컨벤션

| 커밋 유형 | 의미 |
| --- | --- |
| `Feat` | 새로운 기능 추가 |
| `Fix` | 버그 수정 |
| `Docs` | 문서 수정 |
| `Style` | 코드 formatting, 세미콜론 누락, 코드 자체의 변경이 없는 경우 |
| `Refactor` | 코드 리팩토링 |
| `Test` | 테스트 코드, 리팩토링 테스트 코드 추가 |
| `Chore` | 패키지 매니저 수정, 그 외 기타 수정 ex) .gitignore |
| `Design` | CSS 등 사용자 UI 디자인 변경 |
| `Comment` | 필요한 주석 추가 및 변경 |
| `Rename` | 파일 또는 폴더 명을 수정하거나 옮기는 작업만인 경우 |
| `Remove` | 파일을 삭제하는 작업만 수행한 경우 |
| `!BREAKING CHANGE` | 커다란 API 변경의 경우 |
| `!HOTFIX` | 급하게 치명적인 버그를 고쳐야 하는 경우 |

### 🔗 프로젝트 레포지토리

- [Jeonse-ive FE] https://github.com/Jeonse-ive/Jeonse-ive-FE
- [Jeonse-ive BE] https://github.com/Jeonse-ive/Jeonse-ive-BE
- [Jeonse-ive Script] https://github.com/Jeonse-ive/Jeonse-ive-Script


## 가져와서 처음 세팅할 때 필요한 행동

### 1. 조건
- Docker, Docker Compose 설치되어 있어야 합니다.
- `.env` 파일을 구축해야 합니다.

### .env 템플릿:

```bash
DB_USERNAME=your_username
DB_PASSWORD=your_password

REDIS_PASSWORD=your_redis_password

JWT_SECRET_KEY=your_jwt_secret
JWT_ACCESS_EXPIRATION=3600000   # 1시간 (단위: 밀리초)
JWT_REFRESH_EXPIRATION=604800000  # 7일 (단위: 밀리초)
```

### 1.2 BE Build
- BE 디렉터리 위치에서 빌드 명령어를 실행해줍니다.

```bash
./gradlew clean build -x test
```

### 2. 파일 구성

- Dockerfile
- docker-compose.yml
- start script (개발 모드용)


## 실행 방법
```bash
$ ./restart.sh
```
- Spring Boot 서버를 실행합니다.
- 접속 경로: http://localhost:8080
- 실행 시 PostgreSQL(DB)도 함께 시작됩니다.

### 파일 / 구성

| 파일                   | 설명                                     |
|:---------------------|:---------------------------------------|
| `Dockerfile`   | Vite Dev Server를 컨테이너로 실행하는 프론트 개발용 설정 |
| `docker-compose.yml` | db, server port 연결                           |
| `restart.sh`         | 실행 명령어 스크립트                            |


## 참고 사항

- Vite 기본 포트는 5173입니다.
- Spring Boot 기본 포트는 8080입니다.
- PostgreSQL 기본 포트는 5432입니다.
- 프론트엔드 개발 시 API 요청 주소를 http://localhost:8080으로 설정해야 합니다.
---

✨ Tip: Ctrl+C로 서버를 중단할 수 있으며, 컨테이너가 남아있으면 docker ps / docker rm 명령어로 정리해줄 수 있습니다.
