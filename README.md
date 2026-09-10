# 🕹️ Senior Game Server Programmer

13년간 글로벌 대규모 트래픽 환경에서 실시간 멀티플레이어 서버 아키텍처 설계와 라이브 운영 전 과정을 주도해 온 서버 개발자입니다. 단순히 주어진 비즈니스 로직을 구현하는 것을 넘어, 대규모 접속 환경에서도 흔들림 없는 글로벌 분산 아키텍처를 설계하고 잠재적 병목을 선제적으로 차단하는 **'견고한 시스템 구축'**을 지향합니다.

---

## 🚀 Current Deep-Dive (Side Project)
### **[SP.Engine](https://github.com/spilbum/SP.Engine)**: .NET 8 기반 고성능 실시간 게임 서버 엔진
*13년 간의 대규모 실시간 서버 개발 노하우를 집대성하여, GC 스파이크와 락 경합(Lock Contention)을 원천 차단하기 위해 단독 개발 중인 게임 서버 레퍼런스 아키텍처입니다.*

- **Lock-Free Runtime**: 다중 접속 환경의 동기화 병목을 제거하기 위한 Fiber 기반 가상 스레드 큐 내장
- **Zero-Reflection**: 런타임 오버헤드를 배제하기 위해 초기화 시점에 동적 IL(Emit)을 컴파일하는 초고속 패킷 직렬화 파이프라인
- **Hybrid Network & Resumption**: 모바일 환경의 잦은 단선에 대비한 무중단 세션 복구 및 TCP/UDP(가변 MTU 파편화 조립 내장) 하이브리드 스택

---

## 💼 Professional Experience

### **Dodge Royal** (실시간 서바이벌 PvP) | 2024.01 ~ 2024.08
- 글로벌 원빌드 환경에서 다중 리전 RTT 분석 기반의 동적 매칭 시스템을 설계하여 네트워크 레이턴시 최적화
- 동적 코드 생성(IL Emit) 기법으로 MS SQL 연동 시 발생하는 리플렉션 오버헤드를 제거하고 데이터 처리 속도 극대화
- 실시간 대용량 랭킹 갱신의 탐색 비용을 O(1) 수준으로 최적화한 커스텀 자료구조(LinkedList-SortedSet) 설계

### **Mini Golf King** (실시간 PvP 미니 골프) | 2019.08 ~ 2021.10
- 라이브 서비스 중인 프로젝트에 합류하여 CCU 2,000명 규모의 무중단 서버 안정화 및 트러블슈팅 주도
- 주니어 개발자 대상의 깐깐한 아키텍처 피드백과 코드 리뷰를 통해 프로젝트 전반의 퀄리티 방어 및 유지보수성 향상

### **BOWMAX & Pnix.Engine** (실시간 3v3 팀 PvP & 사내 공용 엔진) | 2018.09 ~ 2019.07
- **공용 엔진 개발**: 비동기 스케줄러, 패킷 직렬화, 암호화 등 서버 엔진 내 필수 코어 모듈 구현을 전담하여 전사 프레임워크로 자산화
- **분산 아키텍처**: 매칭 서버와 배틀 서버를 분리한 다대다 분산 로직을 주도적으로 설계 및 구현
- **가용성 검증**: 런칭 전 배틀 서버 자체 스트레스 테스트를 수행하여 시스템 수용 한계 측정 및 병목 선제 해결

### **Rio 2016 Olympic Games** (캐주얼 스포츠) | 2016.01 ~ 2016.10
- 글로벌 트래픽 확장에 유리한 Stateless 기반의 ASP.NET 웹 서버 아키텍처 전담 설계
- 1,000만 유저 처리를 위한 Seed 해싱 기반 MySQL Sharding 및 Redis 활용 글로벌 랭킹 시스템 구축

### **Silkroad Online** (PC MMORPG) | 2012.09 ~ 2014.09
- 방대한 레거시 서버 코드 분석 및 글로벌 라이브 서비스 인게임 에러 신속 대응

---

## 🛠 Technical Skills

| Category | Details |
| :--- | :--- |
| **Languages** | C#, C++ |
| **Frameworks** | .NET 8, .NET Framework, ASP.NET, WPF |
| **Network** | TCP/IP, UDP, WebSocket, HTTP |
| **Database** | MS SQL, MySQL, Redis |
| **Infra & Tools** | AWS (EC2, S3, CloudFront), Git, SVN |

---

## 📊 Stats
![Your GitHub Stats](https://github-readme-stats-one.vercel.app/api?username=spilbum&show_icons=true&theme=radical)

---
📫 **Contact**: spilbum@gmail.com
