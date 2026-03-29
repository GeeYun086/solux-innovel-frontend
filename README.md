# 📖 InnoVel(이노블): 인공지능과 함께 펼치는 무한한 아이디어
![image](https://github.com/user-attachments/assets/ee1bf034-a025-44e8-aadc-e8b772c1d6c4) </br>

> 숙명여자대학교 프로그래밍 중앙동아리 SOLUX 2024-1학기 개발프로젝트 </br>
> 기간 : 2024.03 ~ 2024.08 </br>

</br>

## 🔥 **𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄**

### 𝗕𝗮𝗰𝗸𝗴𝗿𝗼𝘂𝗻𝗱
![image](https://github.com/user-attachments/assets/00b493a8-753a-4516-b6c2-98b7dbe43fd9)
![image](https://github.com/user-attachments/assets/279bdcd9-8113-4de1-ad96-326c6f62e9fc)

- 국내 웹소설 시장의 성장에 따른 웹소설 작가 지망생의 증가 
- 그러나 일반인이 웹소설 창작을 시작하는 것에는 많은 어려움이 있음 


### 𝗚𝗼𝗮𝗹𝘀
![image](https://github.com/user-attachments/assets/7fe0dd07-d8b6-4667-bd7f-38fa4fbb46c8)

- 창의성 촉진 : 사용자에게 영감을 주기 위 다양한 아이디어를 제공함으로써 기존에 존재하지 않는 창의적인 소설 창작을 지원
- 장르 다양성 확장 : 기존 작가들이 익숙하지 않은 장르를 시도해볼 수 있도록 장르별로 독창적인 줄거리를 제공
- 창작 활성화 : 소설 창작에 입문하고자 하는 일반인의 등단을 돕고 다양한 분야의 소설 창작 활동 활성화를 촉진
- 최신 인공지능 기술 활용 : 인공지능 기술을 처음 사용하는 고객도 쉽고 즐겁게 사용할 수 있도록 기능을 구현 

### 𝗜𝗻𝘁𝗿𝗼𝗱𝘂𝗰𝘁𝗶𝗼𝗻

- InnoVel(이노블): `Into + Novel`의 합성어로 `I`와 `V`를 대문자로 강조하여 'AI' 약자처럼 표현함  
- 사용자가 원하는 장르, 테마나 줄거리를 선택하면 인공지능을 기반으로 추천 플롯을 제공하여 소설을 쉽게 창작하고 공유할 수 있는 서비스

</br>

## 💡 **𝗠𝗮𝗶𝗻 𝗣𝗮𝗴𝗲**
![image](https://github.com/user-attachments/assets/1044a583-b044-4251-a54a-a80c8f5b4af2)



</br>

## 🔧 **𝗧𝗲𝗰𝗵 𝗦𝘁𝗮𝗰𝗸**

| **분야**       | **사용 기술**                                 | 
|----------------|---------------------------------------------|   
| **[Frontend](https://github.com/solux-innovel/frontend)**   | React Native, TypeScript                         |
| **[Backend](https://github.com/solux-innovel/backend)**    | Spring Boot, Java   | 
| **Database**   | MySQL(RDS)                       |
| **Open API**        | OpenAI 3.5 turbo  |

</br>

# ✍️ **𝗜𝗻𝗻𝗼𝘃𝗲𝗹-𝗙𝗿𝗼𝗻𝘁𝗲𝗻𝗱** ✍️

## 👥 **𝗠𝗲𝗺𝗯𝗲𝗿𝘀 𝗮𝗻𝗱 𝗥𝗼𝗹𝗲𝘀**

| **이름**            | **역할**              |
|---------------------|-----------------------|
| [**배정연**](https://github.com/bluishflame)  | Frontend, 디자인 |
| [**선수경**](https://github.com/SeonSukyeong) | Frontend |
| [**정지윤**](https://github.com/GeeYun086)     | Frontend |
</br>
> [Innovel 프로젝트 설명 및 전체 팀원 소개 바로 가기](https://github.com/solux-innovel)
</br></br>

## 📂 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗙𝗼𝗹𝗱𝗲𝗿 𝗦𝘁𝗿𝘂𝗰𝘁𝘂𝗿𝗲

```plaintext
frontend/
├── android/                # Android 네이티브 설정 및 빌드 관련 파일
├── ios/                    # iOS 네이티브 설정 및 빌드 관련 파일
├── __tests__/              # 테스트 코드
├── App.tsx                 # 앱 진입점 (AppNavigator 렌더링)
├── index.js                # 앱 등록 파일
├── server.js               # 서버 실행 관련 파일
├── imageGenerator.js       # 이미지 생성 관련 로직
├── package.json            # 프로젝트 의존성 및 설정
├── yarn.lock / package-lock.json  # 패키지 매니저 lock 파일
└── src/
    ├── img/                # 이미지 리소스 (아이콘, 로고, 배너 등)
    │
    ├── navigation/         # 네비게이션 관련 설정
    │   ├── AppNavigator.tsx        # 전체 네비게이션 구조 정의
    │   └── BottomTabNavigator.tsx  # 하단 탭 네비게이션 구성
    │
    ├── screens/            # 화면(Screen) 컴포넌트
    │   ├── Create/         # 소설 생성 화면
    │   ├── Home/           # 홈 화면
    │   ├── Login/          # 로그인 화면
    │   ├── MY/             # 마이페이지 화면
    │   ├── Novel/          # 소설 관련 화면
    │   └── Search/         # 검색 화면
    │
    └── styles/             # 화면별 스타일 정의
        ├── Home/
        └── Novel/
```
</br>

## 🔗 𝗥𝗲𝘀𝗼𝘂𝗿𝗰𝗲𝘀
