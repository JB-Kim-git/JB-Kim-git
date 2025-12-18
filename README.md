# 김중빈

![스크린샷 2025-12-18 오후 5.40.24.png](%EA%B9%80%EC%A4%91%EB%B9%88/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2025-12-18_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.40.24.png)

## 연락처

---

📞 **+82 10-4198-7256**

✉️ orz9852@gmail.com

---

<aside>
<img src="https://www.notion.so/icons/hammer_gray.svg" alt="https://www.notion.so/icons/hammer_gray.svg" width="40px" /> 4년 차 백엔드 개발자로 MAU 50만 & 등록 기기 1000만대의 서비스에서 백엔드 서버 및 플랫폼 개발 등을 해왔습니다.

저는 누구나 쉽게 이해하고 관리할 수 있는 **'심플한 시스템'** 구축을 최우선 가치로 삼습니다. 복잡한 도메인일수록 비즈니스 로직을 명확히 계층화하고 데이터 진입점을 단일화하여, 함께 하는 분들이 기술적 본질에 집중할 수 있는 환경을 만드는 데 보람을 느낍니다.

서비스는 결국 사람과 사람 사이의 커뮤니케이션을 기반으로 완성된다고 생각합니다. 단순히 기능을 구현하는 데 그치지 않고, 동료들과 적극적으로 소통하며 문제의 본질을 함께 정의하고 해결하는 과정을 즐깁니다.

</aside>

# SKILL

---

Languages

Frameworks

Infrastructure

& DataBases

Tools & IDEs

Java

C

Spring Boot

AWS

Kubernetes

Kafka

MySQL

Vim

Jenkins

IntelliJ

Confluence

Grafana

Python

C++

Redis

Docker

Linux

ArgoCD

Git

Gitlab

Jira

Prometheus

Kibana

# EXPERIENCE

---

![LG전자_로고.png](%EA%B9%80%EC%A4%91%EB%B9%88/LG%E1%84%8C%E1%85%A5%E1%86%AB%E1%84%8C%E1%85%A1_%E1%84%85%E1%85%A9%E1%84%80%E1%85%A9.png)

**HS 데이터클라우드개발팀**

2022년 8월~2025년 10월

- LG ThinQ 에너지 서비스 백엔드 API 및 BFF(Backend For Frontend) 설계 및 구축
- 사용자 설정 목표 대비 에너지 사용량 분석 및 푸시 알림 서버 구현
- 사용자 에너지 목표 설정량 대비하여 기기 절전모드 자동 제어 로직 개발
- 에너지 데이터 Open API 서버 구축

# Project

---

### 에너지 서비스 서버 재 구조화

2025년 1월~2025년 9월

- Why : 화면 중심 위주로 API가 설계되어 코드 결합도가 높았고, 신규 기능 추가 시 유지보수 비용과 백엔드 부하 발생
- How : 비즈니스 로직을 표준화한 Platform Layer를 구축하여 화면 중심의 Service Layer와 역할을 분리, Istio Service Mesh의 Traffic Mirroring으로 신규 API를 검증하고, Traffic Splitting을 통해 전환을 수행
- Result : 비즈니스 로직 복잡도를 분산시켜 신규 기능의 독립적 배포가 가능해졌으며, 검증-전환-롤백 체계를 구축
- Skill : Java, Spring Boot, Kubernetes

---

### 신규 서비스 서버 구축

2025년 1월~2025년 2월

- Why : Open API 서비스를 위해 기존 운영 표준을 준수하면서, 독립적인 서버가 필요
- How : Jenkins Pipeline으로 빌드와 ECR 푸시를 자동화, ArgoCD를 활용하여 GitOps 운영 모델을 구현, Vault를 통해 보안 값을 안전하게 분리 관리
- Result : 신규 서버를 성공적으로 런칭하며 빌드부터 배포까지의 전체 라이프사이클을 체득
- Skill : Kubernetes, ArgoCD, Jenkins, AWS ECR

---

### RDB Instance 분리 (읽기/쓰기)

2024년 11월~2025년 3월

- Why : 알림 전송 등 피크 시간대에 DB 대량 조회가 집중되면서 DB Lock 경합과 CPU 부하가 발생
- How : 단일 RDS Instance를 Primary/Read Replica 구조로 전환, 애플리케이션 레벨에서 읽기와 쓰기 경로 분리
- Result : 피크 시간대 DB CPU 사용율을 약 5% 개선, Lock 경합 완화를 통해 p95 지연 속도 개선
- Skill : Python, Java, AWS RDS, MySQL, CloudWatch, Prometheus, Grafana

---

### **이웃집 전력량 계산 로직 개선**

2022년 12월~2023년 4월

- Why : 기존 로직은 '당월 실사용 기기'를 매일 실시간으로 집계해야 했기에, 데이터 양이 늘어날수록 쿼리 부하가 심화
- How : 기획팀과 협의하여 집계 기준을 ‘당월 실사용 기기’에서 ‘등록 기기 전체’로 변경할 것을 제안하고 관점의 전환, 매일 변동되는 실사용 기기 수를 전수 조사하는 복잡한 조인과 집계 쿼리를 제거하고, 기등록 기기 기반의 단순 집계 방식으로 최적화
- Result : 배치 처리 시간을 최대 35분에서 8분으로 약 77% 단축하여 서버 부하를 완화하고 운영 안정성을 확보
- Skill : Java, MySQL

---

# Education

---

![Unist_logo.png](%EA%B9%80%EC%A4%91%EB%B9%88/Unist_logo.png)

**UNIST (울산과학기술원) 석사 - 컴퓨터공학과** 

2020년 9월~2022년 8월

Next-generation Embedded/Computer System Software Technology

Advisor: Prof. Sam H. Noh

---

**UNIST (울산과학기술원) 학사 - 컴퓨터공학과, 인간및시스템공학** 

2014년 3월~2020년 8월
