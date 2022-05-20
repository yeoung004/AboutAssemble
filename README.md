# 🖥️About Assemble

![Group 59](https://user-images.githubusercontent.com/67312562/169484829-3a906018-d059-4836-8cc8-afe46156695a.png)

📍iOS

https://apps.apple.com/us/app/assemble-project-manager/id1623069931

📍Android

https://play.google.com/store/apps/details?id=com.assemble.assembleapp

---

### 📌Goal & Progression

### 🛫출발점

✔️ 취업을 위해 사이드 프로젝트팀원을 찾던 중 프로젝트 관리 + 사이드 프로젝트 커뮤니티 애플리케이션이 없어서 혼자서 이 앱을 개발하게 됐습니다.



### ✈️ 반환점

✔️ 앱을 발전시켜서 음성 회의 기능, 화상 회의 기능, 광고(수익성), 문서편집기능, Web(Next.js), 위젯, 멀티미디어, 테마 등 다양한 기능들을 넣어서 복합적으로 프로젝트를 관리해주는 앱으로 발전시키고 싶습니다.



### 🛬 종착점

✔️ 제가 대학생 때만 해도 깃허브는 선택사항이었던 기억이 납니다. 지금은 개발자가 깃허브를 사용 안 하면 이상하게 생각할 정도로 당연하게 됐듯이 Assemble 앱도 좋은 팀을 꾸려가고 혼자 하던 일을 분산하고, 같은 목표를 가진 사람들과 새로운 깃허브 같은 서비스로 개발하고 싶습니다.

---

### 📌Technology

#### 📱Front End

`React` `React-Native` `Expo` `JS` `TS` `HTML/CSS` `GraphQL` `REST`

#### 🗃️Back End

`AWS RDS` `AWS Cognito` `AWS Amplify` `AWS EC2` `Nginx` `AWS S3` `Firebase Realtime` `Firebase storage` `MySQL` `Python(Crawling)` `Node.js(Express.js)`

#### ⌨️API

`Sendbird API` `Pusher API` 

#### 📍Extension

`Eas cli` `Expo push` `Expo cli` `letsendcrypt(https)` 

#### ⚙️ Architecture

`MVC`

---

![그림1](https://user-images.githubusercontent.com/67312562/169528839-4839b782-9770-49de-a716-27b0c97a56e1.png)

---

### 📌Design

<img src="https://user-images.githubusercontent.com/67312562/169518050-bf57edc9-cf70-416d-b4a4-a919d8174cee.png" alt="Frame 2" style="zoom: 50%;" /><img src="https://user-images.githubusercontent.com/67312562/169518060-bd422f6f-bb96-4165-b695-513cdf95f21a.png" alt="info" style="zoom:50%;" /><img src="https://user-images.githubusercontent.com/67312562/169518061-db91287a-7f22-4754-96ea-f1a09250d318.png" alt="info-1" style="zoom:50%;" /><img src="https://user-images.githubusercontent.com/67312562/169518062-974b6672-2caa-406c-a85a-7d28d70d7293.png" alt="Info-2" style="zoom:50%;" />

`Profile Screen(기존 디자인 총 5번 수정)`

---



![Info 1](https://user-images.githubusercontent.com/67312562/169517040-ef9b7601-bcd6-4f7e-a02b-ad6d04ec74cc.png)![assemble (7)](https://user-images.githubusercontent.com/67312562/169517039-4fd943ea-78a6-4020-8b34-e523382cc883.png)![assemble (6)](https://user-images.githubusercontent.com/67312562/169517037-36c1c0c7-b29a-4a1e-94ae-fce8a550348b.png)

- `Profile Screen`
- `Project Task`
- `Project Daily`

![assemble (4)](https://user-images.githubusercontent.com/67312562/169517034-a9244b74-8686-4572-baf7-ff377dfcb943.png)![assemble (3)](https://user-images.githubusercontent.com/67312562/169517032-48404188-ff21-4631-8170-55e475715324.png)![assemble (1)](https://user-images.githubusercontent.com/67312562/169517022-d8616391-83d8-4a56-b75f-7468be1a21f3.png)

- `Project Main`
- `Projects Main`
- `Chatting Room`



![assemble (2)](https://user-images.githubusercontent.com/67312562/169517030-9d497d33-fdba-4576-b60e-99bd79648811.png)

- `Community`



### 📌 Detail

✔️ 프로젝트는 크게 4가지의 틀로 구성되어 있습니다

#### 1. Auth

- Sign In
- Sign Up
- Confirm
- Forgot Password

#### 2. Content

- Community / Search
- Projects
- Project main(Issue, Task, Daily, Note)
- Posting

#### 3.Chat

- Single Chat
- Group Chat(For Project)
- Chat List

#### 4. Profile

- UserInfo
- Setting

---

### 📌돌아보며

​	 처음으로 만들어보는 서비스였습니다. 그렇기에 많은 시행착오가 있었고, 많은 문제를 맞이했으며, 문제가 어떤건지도 모르는 답답한 상황도 맞이했었습니다. 

처음 앱을 만들기 시작한 git init부터 eas submit 명령어까지 그리고 스토어에 올리면서 가이드라인에 맞지 않아서 5번정도 Reject을 받으며 고치는 순간순간이 돌이켜보면 성장의 기회가 되었습니다. 

공부를 병행하면서 개발하다 보니 전날에는 완벽하다고 생각했던 코드가 다음날 너무 지저분해 보여서 리팩토링을 하다가 한 달이 지났던 것이, 채팅 기능을 넣겠다고 Pusher, Sendbird, Firebase 등 앱에 맞는 최적의 API를 찾기까지 여러 API를 거처가며 지체되는 상황이, 전에는 한 달 동안 아무리 찾아봐도 발견 못한 문제를 지금은 1~2일이면 답을 찾을수 있는 능력을 얻게 될 때, 그만두고 싶다는 말은 사라지고 웃으면서 타이핑을 하는 제 모습을 보니 주니어 개발자인 저에게는 꼭 필요한 시간이었습니다.

출시한 지 얼마 되지않아서 오류 투성이고 지금도 고치고 있지만 언젠가는 Github 처럼 개발자의 필수 툴이 돼서 보다 아름다운 세상을 만드는 개발자가 되었으면 좋겠습니다.
