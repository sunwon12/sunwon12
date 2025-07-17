### 👋 안녕하세요, 꾸준한 성장을 추구하는 백엔드 개발자 정순원입니다.

-   꾸준한 학습과 리팩토링을 통해 **코드 품질과 성능 향상**을 목표로 노력합니다.
-   사용자 경험을 개선하는 **성능 최적화**에 큰 관심을 가지고 있습니다.
-   배움을 공유하기 위해 **블로그**를 꾸준히 운영하며 지식을 나누고 있습니다.

<br/>

### 📧 Contact & 👾 Channel

-   **Email**: jsw5913@naver.com
-   **Phone**: 010-6534-5913
-   **GitHub**: [github.com/sunwon12](https://github.com/sunwon12)
-   **Blog**: [https://jsw5913.tistory.com](https://jsw5913.tistory.com)

<br/>

---

### 🛠️ Tech Stacks

### Programming Languages & Frameworks
![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=java)
![Spring](https://img.shields.io/badge/-Spring-6DB33F?style=flat&logo=spring&logoColor=white)
![JPA](https://img.shields.io/badge/-JPA-007396?style=flat)

### Database
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![AWS RDS](https://img.shields.io/badge/-AWS%20RDS-232F3E?style=flat&logo=amazon-aws)

### DevOps
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/-AWS%20EC2-232F3E?style=flat&logo=amazon-aws)
![AWS S3](https://img.shields.io/badge/-AWS%20S3-232F3E?style=flat&logo=amazon-aws)
![AWS CodeDeploy](https://img.shields.io/badge/-AWS%20CodeDeploy-232F3E?style=flat&logo=amazon-aws)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
<br/>

---

### 🚀 Projects

#### 🍞 건강 디저트 플랫폼, 빵그리의 오븐
**프로젝트 기간: 2024.08 ~ 현재** | **백엔드 (4인)** | **[GitHub](https://github.com/sunwon12)** | **[사이트](https://www.bbanggree.com/)**

> 건강한 베이커리를 찾는 사람들을 위한 판매처 추천 플랫폼 (월 활성 유저 약 300명)

**주요 역할 및 성과**
-   **서버 성능 분석 및 최적화**: VisualVM을 활용하여 메모리 누수를 해결하고, 서버 부팅 시간을 **30분에서 20초로 90배 단축**했습니다.
-   **동시성 이슈 해결**: 리뷰 좋아요 기능에서 발생한 동시성 문제를 **Unique Constraint** 적용으로 간단하고 효율적으로 해결했습니다.
-   **테스트 생산성 향상**: FixtureMonkey를 도입하여 테스트 데이터 생성을 자동화하고, 테스트 작성 시간을 **50% 이상 단축**했습니다.
-   **모니터링 시스템 구축**: AWS CloudWatch, Lambda, Slack을 연동하여 장애 발생 시 실시간 알림 시스템을 구축, **선제적인 대응**이 가능하도록 개선했습니다.
-   **DB 마이그레이션 자동화**: Flyway를 도입하여 수동적인 DB 스키마 관리로 인한 휴먼 에러 가능성을 원천 차단하고 **운영 안정성을 확보**했습니다.
-   **보안 강화**: XSS 공격 방지를 위해 인증 전달 방식을 개선했습니다.
-   **코드 품질 개선**: 반복적인 페이징 및 정렬 로직을 리팩토링하여 코드의 **재사용성과 확장성을 향상**시켰습니다.

---

#### 📚 독서 습관 형성 플랫폼, BookStar
**프로젝트 기간: 2025.05 ~ 현재** | **팀장 및 백엔드 (2인)** | **[GitHub](https://github.com/ssu-capstone-bookstar/server)** | **[앱스토어](https://apps.apple.com/kr/app/bookstar-%EB%B6%81%EC%8A%A4%ED%83%80/id6741843922)**

> 사용자의 독서 습관 형성을 돕는 AI 기반 소셜 리딩 플랫폼

**주요 역할 및 성과**
-   **AI 추천 API 성능 개선**: 백엔드에서 Redis 캐싱을 적용하여 AI 서버 호출을 최소화, 응답 속도를 **70초에서 10ms로 7000배 개선**했습니다.
-   **확장성 높은 아키텍처 설계**: Spring ApplicationEvent 기반의 비동기 이벤트 구조를 도입하여 서비스 간 결합도를 낮추고 **유지보수성과 확장성을 확보**했습니다.
-   **CI/CD 파이프라인 구축**: GitHub Actions를 활용하여 빌드 및 배포 자동화 파이프라인을 구축했습니다.
-   **인증 시스템 리팩토링**: OAuth 2.0/OIDC 기반의 인증 시스템을 고도화했습니다.
-   **주요 기능 개발**: AI 책 추천, 유튜브 영상 추천, 실시간 채팅, 랭킹 시스템 등 핵심 API 개발을 총괄했습니다.

---

#### 🎓 대학생 네트워킹 플랫폼, Flint
**프로젝트 기간: 2023.07 ~ 2023.12** | **백엔드 (3인)** | **[GitHub](https://github.com/sunwon12/Flint-API-Server)**

> 학교 이메일 인증 기반의 대학생 멘토링 및 네트워킹 커뮤니티

**주요 역할 및 성과**
-   **댓글/대댓글 조회 성능 개선**: N+1 문제를 해결하고 쿼리를 최적화하여 응답 속도를 **21,000ms에서 20ms로 1000배 이상 향상**시켰습니다.
-   **이메일 인증 시스템 최적화**: 비동기 처리 및 Redis를 도입하여 이메일 인증 API 응답 시간을 **5초에서 20ms로 250배 단축**하고, Rate Limiting으로 안정성을 강화했습니다.
-   **도메인 설계 최적화**: ENUM과 Converter를 활용하여 명함 도메인의 관심사 테이블 구조를 리팩토링, **테이블 수를 줄이고 조회 성능을 개선**했습니다.
-   **인증/인가 시스템 구축**: Spring Security와 JWT를 활용하여 로그인 및 회원가입 시스템을 구현하고, `@PreAuthorize`를 도입하여 **가독성 높은 인가 처리**를 구현했습니다.

<br/>

---

### 🎓 Education & 🏃 Activities

-   **숭실대학교 소프트웨어학부** (2020.03 ~ 2026.02 졸업예정)
    -   2020년 ‘창의적 공학설계’ 우수상
-   **SCCC (교내 알고리즘 동아리)** (2024.06 ~ 2024.12)
-   **Real MySQL 스터디** (2024.10 ~ 2024.12)
-   **코테이토 (연합 IT 동아리)** (2023.06 ~ 2023.12)

<br/>

---

### 📜 Certificates

-   **SQL 개발자(SQLD)**
-   **정보처리기사 (필기)**
-   **TOPCIT 3수준**
