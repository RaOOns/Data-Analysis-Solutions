# KBO 외국인 투수 스카우팅 최적화

- 목표
    - 스카우팅 시점에서 외국인 투수의 성적을 예측
    - 평가척도: 전달력, 논리성, 실용성, 간결성

- 접근 방식
    - '첫 시즌'부터 좋은 성적을 보여줄 투수를 확보
    - 엘리트 투수 그룹: KBO 영입 후 첫 번째 시즌에서 좋은 성적을 보여준 외국인 투수 그룹을 선정
        - 2011 ~ 2018 활약한 외국인 투수 중
        - 첫 번째 시즌의 평균 자책점(ERA)이 상위 50%에 속하면서, 상대 타자 수 또한 상위 50%에 속하는 그룹
    - KBO 영입 전 MLB에서의 제구력 평가
        - 제구력: 스트라이크 판정된 투구 비중이 10% 이상인 구종의 개수로 정의
- 데이터
    - 2011~2018 KBO에서 활약한 외국인 투수
        - kbo_yearly_foreigners_2011_2018.csv: 역대 KBO 정규시즌 성적
        - fangraphs_foreigners_2011_2018.csv: KBO 입성 전, MLB에서의 역대 정규시즌 성적
        - baseball_savant_foreigners_2011_2018.csv: KBO 입성 전, MLB에서의 스탯캐스터 데이터
    - 2019년 신규 KBO 외국인 투수
        - fangraphs_foreigners_2019.csv: MLB에서의 역대 정규시즌성적
        - baseball_savant_foreigners_2019.csv: MLB에서의 스탯캐스터 데이터
     
- https://dacon.io/competitions/official/68346/overview/description
