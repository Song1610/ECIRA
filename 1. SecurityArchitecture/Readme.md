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
![Image](https://github.com/user-attachments/assets/277cf191-5dd2-4e4d-a30f-4fc55082c69c)

** 그림 수정
대충 이렇게 구성함


__step function 이용 자동화__ <br>
![Image](https://github.com/user-attachments/assets/a5587cfc-bd3e-43b0-ad3d-a14e786b11ba)

** 그림 수정

__CloudTrail 구축__ <br>
![Image](https://github.com/user-attachments/assets/018f6abd-908a-4f81-95be-9ed1472038b2)

** 그림 수정

__CloudTrail Cross Account 구축__ <br>
![Image](https://github.com/user-attachments/assets/56759245-53bb-4e06-b1e4-e2254e8f502b)

** 그림수정
