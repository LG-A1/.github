## 🏠 [Kusitms 32nd X LG] 기업 프로젝트
> 서비스 한 줄 소개

## 🖥️ Developer Members
| **박진우** | **이환석** | **주정빈** | **우다현** |
| :--------: | :------: | :--------: | :--------: |
| <a href="https://github.com/nagosu"><img src="https://avatars.githubusercontent.com/u/100352367?v=4" width="150"> | <a href="https://github.com/hwanseok1014"><img src="https://avatars.githubusercontent.com/u/159034916?v=4" width="150"> | <a href="https://github.com/zyovn"><img src="https://avatars.githubusercontent.com/u/166782961?v=4" width="150"> | <a href="https://github.com/dahyun24"><img src="https://avatars.githubusercontent.com/u/123882512?v=4" width="150"> | 
| `frontend` | `frontend` | `backend` | `backend` |

## 🗂️ ERD
<img width="1939" height="1221" alt="LG-A1 (2)" src="https://github.com/user-attachments/assets/0e02bd06-cf63-4bf3-b5e0-bd29ef507fc4" />

## ⚙️ System Architecture
<img width="1671" height="541" alt="image" src="https://github.com/user-attachments/assets/9cb2081e-1a2f-4fa2-a778-0d2b597e0bb3" />

## 🛠️ 기술 스택

### 💙 Frontend
| 기술 스택               | 설명 |
|------------------------|------|
|React | - 컴포넌트 기반 구조로 UI를 효율적으로 재사용하고 관리<br> - 가상 DOM을 활용해 변경된 부분만 업데이트하여<br>성능과 사용자 경험을 최적화|
|Typescirpt | - 실행 전에 오류를 감지해 버그를 줄이고 안정성을 높임<br> - 명확한 코드 구조로 협업과 유지보수 쉽게 가능|
|Emotion| - 컴포넌트 단위로 일관된 디자인 시스템 구현<br>- props에 따라 동적 스타일링 적용|



### 💚 Backend
| 기술 스택                     | 설명                                                                                                    |
| ------------------------- | ----------------------------------------------------------------------------------------------------- |
| Spring Boot 3.X           | - 최신 기술 적용 가능 (새로운 기능 및 성능 개선)<br>- 유지보수성과 확장성 고려<br>- Java 21 지원으로 성능 최적화 및 최신 기능 활용 가능              |
| GitHub Actions + Docker   | - CI/CD 자동화를 통한 배포 효율성 증가<br>- 컨테이너화를 통한 환경 일관성 유지 및 배포 용이                                            |
| MySQL                     | - 안정성과 성능이 검증된 오픈소스 관계형 데이터베이스<br>- Spring Boot와의 호환성이 뛰어나고 운영 환경에 적합                                 |
| JPA                       | - 객체 지향적인 방식으로 데이터베이스 접근 로직 구현 가능<br>- 반복적인 SQL 작성 없이 생산성과 유지보수성 향상                                   |
| Promtail + Loki + Grafana | - 애플리케이션 및 서버 로그를 중앙집중화하여 수집 및 관리<br>- Grafana 대시보드를 통한 실시간 로그 및 지표 시각화<br>- 문제 발생 시 빠른 원인 분석 및 추적 가능 |
| Prometheus                | - 애플리케이션 및 서버 상태 모니터링<br>- 시계열 기반 메트릭 수집          |
