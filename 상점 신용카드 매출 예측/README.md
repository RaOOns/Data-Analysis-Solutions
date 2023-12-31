# **상점 신용카드 매출 예측**

https://dacon.io/competitions/official/140472/overview/description

- 목적
    - 2016.06.01 ~ 2019.02.28의 신용카드 매출 데이터를 통해 2019.03.01 ~ 2019.05.31의 상점별 3개월 총 매출을 예측
    - 평가 척도: MAE

- 변수
    
    - store_id: 상점의 고유값
    - card_id: 사용 카드의 고유 아이디
    - card_company: 비식별화된 카드회사
    - transacted_date: 거래 날짜
    - transacted_time: 거래 시간(시:분)
    - installment_term: 할부 개월 수 (포인트 사용 시 '60개월 + 실제 할부 개월'을 할부 개월에 기재)
    - region: 상점 지역
    - type_of_business: 상점의 업종
    - amout: 매출액

- 도메인 지식
    1. 자영업자: 많은 상황을 고려
    
        상점은 주중/주말, 공휴일 여부, 오전/오후/심야, 봄/여름/가을/겨울, 학기/방학(성수기/비수기), 리모델링, 계약 만료, 장단기 휴업 등을 고려.

    2. 카드사 직원: 다양한 결제 방식을 제안

        할부, 포인트, 현금 사용, 환불, 재결제 등, 환불 발생 시 매출은 감소하지만 거래 건수는 증가

    3. 고객

        꾸준한 결제, 특수 결제, 계절에 따른 결제, 월급 전후, 경제적 여유, 일상 루틴(교통, 식사, 커피 등)

