# Barrier_Free_Restaurant_app


## 프로젝트 개요
- ‘베리어프리’란 장애인과 노약자들이 시설을 이용할 때 겪는 물리적, 사회적 장벽을 없애 모든 사람이 평등하게 이용할 수 있도록 하는 개념입니다.
- 배리어프리 레스토랑 앱은 장애인과 노약자분들이 편리하게 식당을 이용할 수 있도록 도와주는 서비스입니다.
- 정부에서 제공하는 공공데이터 API를 활용하여 휠체어 경사로, 장애인 화장실, 점자 메뉴 등 배리어프리 시설 정보를 제공합니다. 베리어프리가 보장된 식당을 방문하여, 모두가 평등하게 외식을 즐길 수 있는 환경을 만들고자 합니다.
- 이 프로젝트를 통해 사회적 약자를 위한 실질적인 솔루션을 제공하고, 포용적인 외식 문화를 만드는 것이 목표입니다.


## 주요기능

<img src="https://github.com/user-attachments/assets/9a210bd4-65af-424f-9541-c497f04d6098" width="250" height="550" />
<img src="https://github.com/user-attachments/assets/2e3cff62-f162-4d5c-addb-05ed95dd18fd" width="250" height="550" />
<img src="https://github.com/user-attachments/assets/872d8185-9189-4d0f-afd4-18f370d97688" width="250" height="550" />


- 기본적인 회원가입, 로그인 기능 (Firebase를 통해 구현)

- 네이버 지도를 통해 전국의 베리어프리 식당을 한눈에 볼 수 있음, 마커 구현 및 일정수준의 zoom 넘어가면 클러스터 기술 적용하여 ui 편의 제공.

- 가게를 클릭시 베리어프리 정보를 제공, 즐겨찾기 저장 기능구현,

<img src="https://github.com/user-attachments/assets/dd817826-b91e-4561-ac95-1c138f0dba10" width="250" height="550" />
<img src="https://github.com/user-attachments/assets/3c479cc0-55f4-490f-a244-0205a539044e" width="250" height="550" />
<img src="https://github.com/user-attachments/assets/ae25fa3e-888c-4765-bd2f-49c33a40a12b" width="250" height="550" />


- 정부에서 제공하는 데이터, 그 범위 안에수 지역, 메뉴, 상호 등을 통한 검색 기능 구현.

- 데이터 로드에 부담을 줄이기 위해서, 검색결과를 한번에 제공하지 않고 초기에 10개 제공 후, 스크롤이 바닥에 닿았을때 3개씩 추가 로드하도록 PageNation 구현.

- 즐겨찾는 저장한 음식점을 보여주고, 해당 음식점과 같은 동네에 있는 음식점을 지역위치를 기밤으로 추천하는 기능 제공.




