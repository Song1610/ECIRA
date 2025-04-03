# AWS 보안아키텍처 구축 TEST
## 작업내용 목차
1. security hub automation 적용
2. security hub를 통해 수집된 서비스별 이벤트를 식별 및 알림체계 구성
    - 서비스 : guardduty, inspector, config
    - 알림방식 : 이메일, slack, teams 등
3. CloudTrail 이벤트를 통해 수집된 서비스별 이벤트를 식별하고 알림체계 구성
    - 알림방식 : 이메일, slack 등
4. 책임자의 이메일/슬랙 등을 통해 실행되는 Runbook 구축
---

### Security Hub Automation 적용
채우기

### Security Hub를 통해 수집된 서비스별 이벤트 식별 및 알림체계 구성

#### 흐름도 및 구성
__Security Hub(GuardDuty, Inspector, Configs) 흐름도__ <br>

<img width="704" alt="Image" src="https://github.com/user-attachments/assets/54875d25-397b-4ef6-93d2-eb08eb02503e" />

__step function 이용 자동화 구성__ <br>
<img width="442" alt="Image" src="https://github.com/user-attachments/assets/41df2ff5-f28b-4aaf-8c32-d0886cc5b6ed" />

** 그림 수정

__CloudTrail 구축__ <br>
![Image](https://github.com/user-attachments/assets/018f6abd-908a-4f81-95be-9ed1472038b2)

** 그림 수정

__CloudTrail Cross Account 구축__ <br>
![Image](https://github.com/user-attachments/assets/56759245-53bb-4e06-b1e4-e2254e8f502b)

** 그림수정
