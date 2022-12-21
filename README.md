 <h1> 시각장애인을 위한 길 안내 서비스
 <h2> 주제 선정 배경
   <h5> 1) 시각장애를 가지고 있으신 분들이 집 밖을 나서서 혼자서 대중교통을 이용하여 목적지로 가는 것은 큰 부담으로 다가올 수 있다.
   <h5> 2) 안내견을 데리고서 버스 이용의 어려움
 <h2> 구현 목표
   <h3> 1) 목적지까지 안전한 보행
     <h4> - 인공지능을 사용한 물체 식별 및 음성 안내
       <h5> 1차 목표 : 장애물과의 거리 인식
       <h5> 2차 목표 : 장애물의 종류 인식
     <h4> - GPS 및 지도를 이용한 길 안내
       <h5> m 단위의 거리 개념이 익숙치 않기때문에 이용자의 평균 포복을 계산하여 걸음 수로 안내 
   <h3> 2) 적절한 버스 정보 제공
     <h4> - 실시간 버스 위치 정보
       <h5> 공공데이터포털에서 제공하는 국토교통부의 버스위치정보 open API 사용
     <h4> - 어떤 버스를 타야 하는가?
       <h5> 버스기사 회원가입시 운행하는 노선번호를 입력 받아 DB에 저장
       <h5> 가까운 정류장에 이용자가 있을 경우 버스기사님께 알림
   <h3> 3) 쉽고 편리한 이용
     <h4> - 음성 안내와 음성 인식
       <h5> 사용자의 시각을 고려하여 버튼을 클릭시 TTS 및 AI 음성을 이용하여 청각 정보 제공
       <h5> 타자를 치기 어려움을 고려하여 STT를 음성을 통한 검색 지원
     <h4> - 접근성을 높인 디자인
       <h5> 시각장애가 있어도 노란색은 인지가 가능한것과 노란색의 보색인 검정색을 사용하여 인식의 편리함
       <h5> 크고 단순한 버튼 사용
       




