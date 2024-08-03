![스크린샷 2024-08-04 025836](https://github.com/user-attachments/assets/5859bd85-7e21-40c6-8dbf-3c51507d8759)# 프로젝트 소개
MIDPOINT : 우리 어디서 만날까?

중간값 알고리즘을 사용한
사용자의 목적에 맞는 중간 지점 찾기 서비스 

## 1. 프로젝트 동기 
### 만남 장소에서 발생할 수 있는 문제점
- 여러 사람이 만날 때 모임 장소를 정하는 데 어려움이 있음
- 모두가 아는 장소로 와야 하는 문제
- 시간과 비용이 비효율적으로 소모됨
- 중간 지점을 찾아도 목적에 맞는 장소를 재검색해야 함

### 이에 대한 해결책
- 중간 지점에서 만남
   - 모두에게 시간적으로 유리
   - 공평한 장소 선정 가능
- 만남 목적 반영
   - 만남의 목적에 맞는 장소 제공
   - 장소 선택에 대한 번거로움 감소
   - 특정 활동에 적합한 장소 선정으로 모임의 질 향상

## 2. 팀원 소개 및 역할분담
<img width="485" alt="image" src="https://github.com/user-attachments/assets/ca193b43-625b-4c80-a44e-1779969fa039">
<img width="485" alt="image" src="https://github.com/user-attachments/assets/cb137720-120c-4f4d-9aa3-98212269ca31">
<img width="485" alt="image" src="https://github.com/user-attachments/assets/03dbcc5c-b67c-4ae2-ae69-55eaf3a597be">

## 3. 프로젝트 아키텍처
<img width="485" alt="image" src="https://github.com/user-attachments/assets/f94ac091-0dfd-4697-b745-c39d0df5c450">

## 4. 메뉴 구조 
<img width="485" alt="image" src="https://github.com/user-attachments/assets/6f08a7ca-d15c-44c0-a06e-4da7d7d2202a">

현 프로젝트는 크게 로그인 페이지, 홈 화면 페이지, 게시판 페이지, 마이페이지로 구성되어 있습니다. 

웹 페이지의 상단의 네비게이션 바를 통해 해당 페이지로 이동하실 수 있습니다. 

## 5. 구현 기능 소개 
<img width="485" alt="image" src="https://github.com/user-attachments/assets/e2924981-15f6-46ef-92dd-b9ee6d46c7f0">
<img width="485" alt="image" src="https://github.com/user-attachments/assets/856b0381-212c-4f98-ac33-9bd10afa6682">

## 6. 페이지 캡쳐
### 1. 로그인 페이지 
![스크린샷 2024-08-04 023654](https://github.com/user-attachments/assets/a1f71d48-0d95-4d74-9b97-2f738f593c79)

### 1.1 카카오 로그인 페이지
![스크린샷 2024-08-04 023721](https://github.com/user-attachments/assets/9579b6fb-b4dc-44f8-8ba2-9fccbb07d460)

### 1.2 자체 로그인 페이지 
사용자는 '아이디' 칸에 아이디 또는 이메일로 입력합니다. 
비밀번호가 일치하지 않으면 '아이디 또는 비밀번호가 일치하지 않습니다' 에러 문구가 뜹니다.
![스크린샷 2024-08-04 025547](https://github.com/user-attachments/assets/0f255be6-da5f-4d21-aade-e27637b04a02)


### 2. 홈 페이지
- 로그인을 하지 않은 상태라면 즐겨찾기 장소나 즐겨찾기 친구를 클릭해도 '로그인 후 이용해주세요' 라는 문구가 뜹니다.
- 아래 '검색 기록'에 현재 페이지에서 사용자가 검색한 장소 리스트들이 뜹니다.
![스크린샷 2024-08-04 025757](https://github.com/user-attachments/assets/eccecc4b-1150-42b9-8cf2-b9a835d4c71a)

- 주소와 목적을 적절히 선택합니다. 
![스크린샷 2024-08-04 025813](https://github.com/user-attachments/assets/899755bc-78cb-4693-8062-dd099994db8a)


### 3. 장소 페이지
- 다음과 같이 목적에 맞는 장소들 리스트가 왼쪽에 나오고, 오른쪽에는 중간지점 위치를 마커로 찍은 map이 나옵니다.
![스크린샷 2024-08-04 025836](https://github.com/user-attachments/assets/bd8736b3-6f12-49ab-84e0-c1b3b08f5c96)

- 해당 장소를 클릭하면 리뷰 페이지로 넘어갑니다. 
![스크린샷 2024-08-04 025847](https://github.com/user-attachments/assets/33170ca1-c168-4926-ba62-cbe526ef6ff2)

- 장소 저장이나 공유를 하고 싶은 경우 '장소 선택'을 누른 뒤 '공유' 또는 '장소 저장' 버튼을 클릭합니다. 
![image](https://github.com/user-attachments/assets/f3b7c4d4-be53-4090-b300-e2db144aa459)



회원가입 페이지

## 6. 관련 주소
- <a href="https://www.figma.com/design/QzDsktNnMnGtNBkqlKDQYj/%EC%86%94%EB%A3%A9%EC%85%98?node-id=3824-2402&t=O6WUCFepPLPCAHbg-1">Figma Address</a>
- <a href="https://github.com/Solucitation/midpoint-backend">BE Address</a>
- <a href="https://github.com/Solucitation/midpoint-frontend">FE Address</a>
