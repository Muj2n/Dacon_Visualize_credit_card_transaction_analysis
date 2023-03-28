# 신용카드 거래 데이터 시각화(뱅크샐러드) 경진대회

------------------
- ***컬럼 (column) 설명***
    - store_id : 각 파일에서 상점 고유 번호
    - date : 거래 일자
    - time : 거래 시간
    - card_id : 카드번호 hash 값
    - amount : 매출액, 0보다 작은 음수는 거래 취소(환불) / 할부개월수만큼 amount 들어옴
    - installments : 할부개월수, 일시불은 빈 문자열
    - days_of_week : 요일, 월요일이 0, 일요일이 6
    - holyday : 1이면 공휴일, 0이면 공휴일 아님
---------------------------

- ***느낀점***

시각화에 있어서 Seaborn의 중요성을 알게 되었고, 또한 날짜와 시간의 데이터를 이용한 인사이트 도출을 공부해보고 적용해보는 실습이 필요하다 느꼈다.

또한, 데이터 분석에서의 시각화의 과정이 다양하다는 것을 느꼈고, 이를 통해 분석 시 인사이트 도출에 있어서의 방향과 그를 통한 분석을 다양하게 수행해봐야겠다고 느꼈다. 또한, 데이터 분석에 있어서 시각화 뿐만 아니라 Tableau사용 및 좌표가 데이터로 주어졌을 때 이를 지도에 나타는 방법까지도 다양하게 수행해 봐야겠다고 느꼈다.
