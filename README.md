시각장애인을 위한 스마트 지팡이
=============

>**프로젝트 기간**: 2020.11.26 ~ 2020.12.10

</br>

>**구현 기능**
>* use_stick.py
>1. 주변 밝기 감지를 통한 LED ON/OFF 구현
>2. 절사평균을 이용한 거리 측정
>3. 장애물 거리별 경고음 발생
>* find_stick.py
>1. DDNS를 이용하여 웹 서버의 도메인 네임 생성
>2. 지팡이 분실 시 찾기 및 중단 웹 구현
>3. 웹 페이지에서 FIND 버튼 클릭 -> LED ON, 부저 ON, OLED에 사용자 정보 출력
>4. 웹 페이지에서 STOP 버튼 클릭 -> LED OFF, 부저 OFF, OLED CLEAR

</br>

### [회로 구성도]

><img src="https://github.com/ejshin004/IoT_Project/assets/55674729/eee1990f-649e-48ad-85c5-37b966d13a90" width="70%" height="30%"></img>

</br>
</br>

### [웹 페이지]

><img src="https://github.com/ejshin004/IoT_Project/assets/55674729/608efa94-c6a2-4ca2-9cd2-20abc5d07361" width="70%" height="30%"></img>
><img src="https://github.com/ejshin004/IoT_Project/assets/55674729/664ae756-b0b1-4abd-b168-e31acae05267" width="70%" height="30%"></img>
