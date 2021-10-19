# ICT-HydrogenDistributionCenter
ICT 전시회에 전시할 블록체인 기반 수소 유통 센터 프로젝트

</br>

## 🗓 개발 일정

- 10.18 ~ 10.22 : 요소 기술 파악 및 전시회 행정 처리
- 10.25 ~ 10.29 : 요소 기술 개발 킻 구축
- 10.26 ~ 11.12 : 요소 기술 통합

</br>

## 💡 목적, 내용, 적용분야

### 목적
- 에너지 거래내역, 입찰 및 정산 등을 블록체인으로 위 변조 방지 및 신뢰도 향상
- 블록체인 기반 분산 데이터 저장을 통해 외부 공격이나 데이터 손상으로부터 보호 및 유실 방지
- 제 3자를 배제시켜 에너지 거래 유통 과정의 축소를 통해 유통의 효율성 증대 및 비용 절감

### 내용

- 이더리움 기반의 수소 유통 센터 시나리오
- 수소 수급 관리를 위한 수소 유통 센터의 기능들을 블록체인 시스템으로 적용
- 수소충전소, 한국가스공사(수소 유통센터), 수소 생산자, 운송업체가 블록체인 네트워크에 참여하여 수소 유통 관리
- 스마트 컨트랙트를 통한 수소거래, 수소 충전 및 결제 자동화 기능 제공
-수소 유통관리에서 일어나는 내역들은 블록체인의 분산원장으로 기록

### 적용분야

- 신 재생 에너지 유통 분야

</br>

## ✏️ 시나리오
1. 수소 소비자는 수소 충전을 하기 위해서 수소 충전소로 이동한다.
2. 수소 충전소에 도착한 사용자는 지갑을 이용해서 충전할 수소 양과 해당되는 금액을 지불한다. 
3. 수소 1L당 코인 100개라고 가정한다.
4. 수소 충전소는 지갑을 통해서 충전소에 저장된 수소가 빠져나간것이 확인하고, 사용자에 의해 코인이 들어온 것을 확인한다.
5. 수소 충전소는 충전소 수소를 충전하기 위해서 지갑을 통해 수소 생산자에게 수소 충전 요청을 한다. 
6. 수소 생산자는 수소 충전소에 응답을 받으면 지갑을 통해 운송업체를 호출한다.
7. 운송업체는 수소 충전소에 도착하고 수소 차량에 수소를 충전한다.
8. 운송업체는 충전소에 도착하여 수소 차량에 있는 수소를 확인하고 지갑을 통해서 수소 충전 완료를 누른다.
9. 소수 생산자의 지갑에서는 배달이 완료됨이 확인되면 자동으로 코인이 빠져 나가서 운송 업체에 지불된다..
10. 운송업체 지갑에는 자동으로 코인이 충전된다.
11. 수소 충전이 완료되면 수소 충전소는 자동으로 코인을 수소 생산자에게 지불된다.

</br>

## ✅ 필요한 UI
  - 수소 충전소 지갑 : 코인 보유량, 수소 보유량, 수소 충전 요청
  - 수소 생산자 지갑 : 코인 보유량, 수소 보유량, 수소 충전 요청 ON/OFF, 운송 업체 호출
  - 수소 소비자 지갑 : 코인 보유량, 수소 보유량, 수소 충전
  - 수소 운송업체 지갑 : 코인 보유량, 수소 보유량, 배달 완료
  - 모니터링 : 검색, 실시간 트랜잭션, 블록생산, 실시간 수소 이동 현황
 
</br>

## 💻 Programming Language
  - Node.js

