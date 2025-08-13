
# [Dear-Carmate 개발 보고서]  


프로젝트명 : [Dear-Carmate 프로젝트  

팀명: 3팀  

작성자: 이종진  

작성일: 2025-08-13

---


# 1. 📝 프로젝트 개요

 
### 1.1 목적 

 
🚗 중고차 계약 관리 서비스 DearCarmate<br/>
     중고차 계약, 간편하고 스마트하게
     복잡한 계약 관리, 이젠 한 곳에서 해결하세요.

 
### 1.2 주요 기능

 
- 인증 API
- 유저 API
- 차량 API
- 고객 API
 
- 회사 API
- 계약 API
- 계약서 API
  
- 대시보드 API
- 이미지 API 
---
 
# 2. ⚙️ 기술 스택 및 협업 도구
 
 
<h3 align="center"><b>📚 Languages 📚</b></h3>

<p align="center"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" /> 
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" /> </p>

<h3 align="center"><b>⚙️ Frameworks & Libraries</b></h3>

<p align="center"> <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" /> <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" /><br/>  <img src="https://img.shields.io/badge/Passport-34E27A?style=for-the-badge&logo=passport&logoColor=white" /> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" /> <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" /> <img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black" /> </p>

<h3 align="center"><b>🗄️ Database & Hosting</b></h3>

<p align="center"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Render-0099E5?style=for-the-badge&logo=render&logoColor=white" /> </p>

<h3 align="center"><b>🔧 Development Tools </b></h3>

<p align="center"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /> <img src="https://img.shields.io/badge/Nodemon-76D04B?style=for-the-badge&logo=nodemon&logoColor=white" /> <img src="https://img.shields.io/badge/TS Node-3178C6?style=for-the-badge&logo=ts-node&logoColor=white" /> <img src="https://img.shields.io/badge/Dotenv-ECD53F?style=for-the-badge&logo=dotenv&logoColor=black" /> </p>


<h3 align="center"><b>🔐 Authentication & Utility Libraries </b></h3>
<p align="center">
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" alt="JWT" />
  <img src="https://img.shields.io/badge/Nodemailer-009966?style=for-the-badge&logo=gmail&logoColor=white" alt="Nodemailer" />
  <img src="https://img.shields.io/badge/Multer-1E90FF?style=for-the-badge&logo=files&logoColor=white" alt="Multer" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
</p>

<h3 align="center"><b> 🤝 Collaboration Tools </b></h3>
<p align="center"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" alt="Notion" /> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /> <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /> </p>
---
 
# 3. 📌 담당한 작업 

 
### 3.1 고객 등록

- 고객명, 성별, 연락처, 연령대, 지역, 이메일, 메모를 입력하여 고객 등록이 가능합니다.
- 연령대, 지역, 이메일, 메모는 선택 사항입니다.

---
### 3.2 고객 수정  

- 유저의 회사에 등록된 고객 정보의 수정이 가능합니다

---
### 3.3 고객 삭제

- 유저의 회사에 등록된 고객 정보의 삭제가 가능합니다.

---
### 3.4 고객 목록 조회
- 등록된 고객 정보 목록을 확인할 수 있습니다.
- 고객명, 계약 횟수, 성별, 연락처, 연령대, 지역, 이메일이 표시됩니다.
- 페이지네이션이 가능합니다.
- 고객명, 이메일로 검색이 가능합니다.
---  

### 3.5 계약서 등록  
- 거래를 선택하고 계약서 파일을 추가하여 등록합니다.
- 유효한 확장자의 파일만 업로드 가능합니다.
- 업로드 파일 개수, 용량 제한이 있습니다.
- 계약서가 등록될 경우 고객에게 자동으로 계약서가 첨부된 이메일이 발송됩니다.
---  


### 3.6 계약서 다운로드
- 업로드 된 계약서 일부 혹은 전체를 다운로드 할 수 있습니다.
---

### 3.7 계약서 수정
- 등록된 계약서의 일부 혹은 전체를 삭제할 수 있습니다.
- 계약서를 추가로 등록할 수 있습니다.
- 계약 수정 API를 활용해서 구현해주세요.



### 3.8 계약서 목록 조회

- 등록된 계약서 목록을 확인할 수 있습니다.
- 계약서명, 계약체결일, 문서 수, 담당자, 차량번호가 표시됩니다.
- 페이지네이션이 가능합니다.
- 계약서명, 담당자로 검색이 가능합니다.

# 4. 📌 개발 예시  


### 4.1 고객 등록  

- API URL(POST /customers) & 요청 예시
  
- 응답 예시 (201 Created)
 ```
 {
	"id": 123,
	"name": "string",
	"gender": "male | female",
	"phoneNumber": "string",
	"ageGroup": "10대 | 20대 | 30대 | 40대 | 50대 | 60대 | 70대 | 80대",
	"region": "서울 | 경기 | 인천 | 강원 | 충북 | 충남 | 세종 | 대전 | 전북 | 전남 | 광주 | 경북 | 경남 | 대구 | 울산 | 부산 | 제주",
	"email": "string",
	"memo": "string",
	"contractCount": 0
}
```
  
<img width="835" height="641" alt="고객 등록" src="https://github.com/user-attachments/assets/11a3ce6c-ab9e-450e-b127-33500e8c6ab8" />



### 4.2 고객 목록 조회  

- API URL(GET  고객	/customers) & 요청 예시
  
- 응답 예시 (200 OK)
```
{
	"currentPage": 1,
	"totalPages": 5,
	"totalItemCount": 50,
	"data": [
		{
			"id": 1,
			"name": "string",
			"gender": "male | female",
			"phoneNumber": "string",
			"ageGroup": "10대 | 20대 | 30대 | 40대 | 50대 | 60대 | 70대 | 80대",
			"region": "서울 | 경기 | 인천 | 강원 | 충북 | 충남 | 세종 | 대전 | 전북 | 전남 | 광주 | 경북 | 경남 | 대구 | 울산 | 부산 | 제주",
			"email": "string",
			"memo": "string",
			"contractCount": 0
		},
		{
			"id": 2,
			"name": "string",
			"gender": "male | female",
			"phoneNumber": "string",
			"ageGroup": "10대 | 20대 | 30대 | 40대 | 50대 | 60대 | 70대 | 80대",
			"region": "서울 | 경기 | 인천 | 강원 | 충북 | 충남 | 세종 | 대전 | 전북 | 전남 | 광주 | 경북 | 경남 | 대구 | 울산 | 부산 | 제주",
			"email": "string",
			"memo": "string",
			"contractCount": 0
		}
	],
}
```
  
<img width="841" height="683" alt="고객 목록 조회" src="https://github.com/user-attachments/assets/69cd4b86-918d-4c4b-b06e-ec8de73b93b4" />





### 4.3 고객 수정

- API URL(PATCH /customers/{customerId}) & 요청 예시
  
- 응답 예시 (200 OK)

  
```
{
	"id": 123,
	"name": "string",
	"gender": "male | female",
	"phoneNumber": "string",
	"ageGroup": "10대 | 20대 | 30대 | 40대 | 50대 | 60대 | 70대 | 80대",
	"region": "서울 | 경기 | 인천 | 강원 | 충북 | 충남 | 세종 | 대전 | 전북 | 전남 | 광주 | 경북 | 경남 | 대구 | 울산 | 부산 | 제주",
	"email": "string",
	"memo": "string",
	"contractCount": 0
}
```


<img width="837" height="655" alt="고객 수정" src="https://github.com/user-attachments/assets/0fbfb5cc-e701-43a6-a949-cb84f2a7c68e" />




### 4.4 고객 삭제

- API URL(DELETE /customers/{customerId}) & 요청 예시
  
- 응답 예시 (200 OK)
  
```
{
  "message": "고객 삭제 성공"
}
```

<img width="843" height="539" alt="고객 삭제" src="https://github.com/user-attachments/assets/c53a6439-9a28-4d72-b57b-684c0e40db1e" />


### 4.5 고객 상세 정보 조회

- API URL(GET /customers/{customerId}) & 요청 예시
```
{
	"id": 123,
	"name": "string",
	"gender": "male | female",
	"phoneNumber": "string",
	"ageGroup": "10대 | 20대 | 30대 | 40대 | 50대 | 60대 | 70대 | 80대",
	"region": "서울 | 경기 | 인천 | 강원 | 충북 | 충남 | 세종 | 대전 | 전북 | 전남 | 광주 | 경북 | 경남 | 대구 | 울산 | 부산 | 제주",
	"email": "string",
	"memo": "string",
	"contractCount": 0
}
```

<img width="853" height="647" alt="고객 상세 조회" src="https://github.com/user-attachments/assets/0cff8054-5c01-401e-b614-bcd1cba68506" />

### 4.6 고객 데이터 대용량 업로드

- API URL(POST /customers/upload) & 요청 예시

```
{
	"message": "성공적으로 등록되었습니다"
}
```
<img width="869" height="517" alt="고객 대용량 업로드" src="https://github.com/user-attachments/assets/fd0237b7-4f7a-4522-8b24-bb7091f25266" />



### 4.7 계약서 업로드 시 계약 목록 조회

- API URL(GET /contractDocuments) & 요청 예시

- 응답 예시 (200 OK)
```
{
	"currentPage": 1,
	"totalPages": 2,
	"totalItemCount": 6,
	"data": [
		{
			"id": 1,
			"contractName": "string",
			"resolutionDate": "2024-02-22T09:00:00.000Z",
			"documentsCount": 2,
			"manager": "string",
			"carNumber": "string",
			"documents": [
				{
					"id": 1,
					"fileName": "string"
				},
				...
			]
		},
		...
	]
}
```
<img width="850" height="605" alt="계약서 업로드 시 목록 조회" src="https://github.com/user-attachments/assets/1942db0d-c07b-4430-ad2e-cf5ab4dcc5c0" />


### 4.8 계약서 추가 시 계약 목록 조회

- API URL(GET /contractDocuments/draft) & 요청 예시

- 응답 예시 (200 OK)
```
[
	{
		"id": 1,
		"data": "그랜저 - 김고객 고객님"
	},
	{
		"id": 2,
		"data": "K3 - 홍길동 고객님"
	},
	...
]

```
<img width="848" height="674" alt="계약서 추가용 계약 목록 조회" src="https://github.com/user-attachments/assets/9ebdb680-e591-49d8-becd-621d5b483622" />


### 4.9 계약서 업로드

- API URL(POST /contractDocuments/upload) & 요청 예시

- 응답 예시 (200 OK)
```
{
	"contractDocumentId": 1
}

```

<img width="873" height="602" alt="계약서 업로드" src="https://github.com/user-attachments/assets/1891f7cb-3713-4ea6-8d41-fa5ea73b4772" />


### 4.10 계약서 다운로드

- API URL(GET /contractDocuments/{contractDocumentId}/download) & 요청 예시

- 응답 예시 (200 OK)
```
{
	"message": "계약서 다운로드 성공"
}


```
<img width="859" height="658" alt="계약서 다운로드 에러 메세지" src="https://github.com/user-attachments/assets/58dc25b7-c90d-4fe4-8ff5-7cf94256fae6" />


---



# 5. 📌 파일 구조 
 
## 파일 구조 
```
├─ .eslintrc.json
├─ .gitignore
├─ .prettierrc.json
├─ .vscode
│  └─ setting.json
├─ README.md
├─ package-lock.json
├─ package.json
├─ prisma
│  └─ migrations
│  └─ schema.prisma
│  └─ mock.ts
│  └─ seed.ts
├─ src
│  ├─ @types
│  │  └─ express
│  │     └─ index.d.ts
│  ├─ app.ts
│  ├─ auth
│  │  ├─ auth.routes.ts
│  │  ├─ auth.ts
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  └─ login.dto.ts
│  │  ├─ jwt.ts
│  │  ├─ passport.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ cars
│  │  ├─ cars.routes.ts
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  └─ create-car.dto.ts
│  │  │  └─ get-car.dto.ts
│  │  │  └─ update-car.dto.ts
│  │  │  └─ upload-car.dto.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ common
│  │  ├─ constants
│  │  │  └─ constants.ts
│  │  ├─ enums
│  │  │  ├─ age-group.enum.ts
│  │  │  ├─ car-status.enum.ts
│  │  │  ├─ car-type.enum.ts
│  │  │  ├─ contract-status.enum.ts
│  │  │  ├─ gender.enum.ts
│  │  │  └─ region.enum.ts
│  │  ├─ errors
│  │  │  ├─ app-error.ts
│  │  │  ├─ bad-request-error.ts
│  │  │  ├─ conflict-error.ts
│  │  │  ├─ forbidden-error.ts
│  │  │  ├─ not-found-error.ts
│  │  │  └─ unauthorized-error.ts
│  │  ├─ prisma
│  │  │  └─ client.ts
│  │  └─ utils
│  │     ├─ custom-errors.ts
│  │     └─ validate.dto.ts
│  │     └─ car.converter.ts
│  │     └─ contract.converter.ts
│  │     └─ csv-downloader.ts
│  │     └─ customer.converter.ts
│  │     └─ firebase-admin.ts
│  ├─ companies
│  │  ├─ companies.routes.ts
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  ├─ create-company.dto.ts
│  │  │  ├─ get-companies.dto.ts
│  │  │  ├─ get-users.dto.ts
│  │  │  └─ update-companies.dto.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ contract-documents
│  │  ├─ contract-documents.routes.ts
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  ├─ download-contract-documents.dto.ts
│  │  │  ├─ edit-contract-documents.dto.ts
│  │  │  ├─ get-contract-documents.dto.ts
│  │  │  └─ upload-contract-document.dto.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ contracts
│  │  ├─ contracts.routes.ts
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  ├─ create-contract.dto.ts
│  │  │  ├─ meeting.dto.ts
│  │  │  └─ update-contract.dto.ts
│  │  │  └─ update-meeting.dto.ts
│  │  ├─ contract.mapper.ts
│  │  ├─ repository.ts
│  │  ├─ schema.ts
│  │  └─ service.ts
│  ├─ customers
│  │  ├─ controller.ts
│  │  ├─ customers.routes.ts
│  │  ├─ dto
│  │  │  ├─ create-customer.dto.ts
│  │  │  ├─ customer-list-query.dto.ts
│  │  │  ├─ update-customer.dto.ts
│  │  │  └─ upload-customers.dto.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ dashboard
│  │  ├─ controller.ts
│  │  ├─ dashboard.routes.ts
│  │  ├─ dto
│  │  │  ├─ contract-by-car-type.dto.ts
│  │  │  ├─ sales-by-car-type-raw.dto.ts
│  │  │  ├─ sales-by-car-type.dto.ts
│  │  │  └─ summary-response.dto.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ index.routes.ts
│  ├─ main.ts
│  ├─ middlewares
│  │  ├─ auth.middleware.ts
│  │  └─ error.middleware.ts
│  ├─ uploads
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  └─ upload.dto.ts
│  │  ├─ repository.ts
│  │  ├─ service.ts
│  │  └─ uploads.routes.ts
│  └─ users
│     ├─ controller.ts
│     ├─ dto
│     │  ├─ create-user.dto.ts
│     │  └─ update-user.dto.ts
│     ├─ repository.ts
│     ├─ service.ts
│     └─ users.routes.ts
└─ tsconfig.json
```

---  

# 6. 🗒️ 테스트 계획서 및 보고서  

[테스트 계획서] (https://www.notion.so/seven-210a1c7d0d6a80269a25f5476a37c7a3)  

[테스트 보고서] (https://www.notion.so/seven-1f9a1c7d0d6a8089bffce49da0f0520a)  

---  


# 7. 📌 문제점 및 해결 과정  

### 7.1 git pull upstream main을 진행하지 않고 로컬에서 작업하다 충돌  

: git stash를 이용하여 임시 저장하고 난 다음 git pull upstream main 진행, 
  후에 충돌 마커 확인하면서 충돌 해결  

---  

### 7.2 코딩 컨벤션 맞추는 데 어려움을 느낌(필드명 통일이나 대소문자 통합 등)  

: 데일리 스크럼 외에도 주기적으로 팀원들과 소통하며 맞추려고 노력  

---  


### 7.3 커밋을 잔뜩 쌓아두고 진행하다가 충돌이 났는데, 충돌 발견도 어려울 뿐더러 해결도 힘듦  


: 해당 PR을 닫은 후, 새로 처음부터 다시 시작  

---  


### 7.4 GroupRecommend 모델과 Participant 모델에 unique가 없어서 에러 발생  

: [@@unique([groupId, userId]) // 복합 유니크 제약 조건 추가로 에러 해결  

--- 


### 7.5 mock 데이터와 seed 데이터를 받아왔는데, seed 파일 내 경로가 mockData라 데이터를 못 받아오는 문제 발생  


: 경로를 파일명과 일치하게 mock로 변경  


```
const { GROUPS, TAGS, USERS, EXERCISE_RECORDS, GROUP_RECOMMENDS, RANKS, PHOTOS, PARTICIPANT } = require('./mockData');
```
```
const { GROUPS, TAGS, USERS, EXERCISE_RECORDS, GROUP_RECOMMENDS, RANKS, PHOTOS, PARTICIPANT } = require('./mock');
```

---  


### 7.6 swagger 테스트 중 postman과 newman 등을 이용하여 자동 테스트가 안되는 문제  

: swagger 폴더에 swagger.js(info, title 내용 들어있는 부분)와 // Swagger/OpenAPI 문서를 JavaScript 객체로 조립하는 구조 openapi.yaml(summary 내용 들어있는 부분) 이렇게 두 파일로 나눴는데, 하나의 파일로 합침

---


# 8. 📃 회고록(느낀 점)
 
### 8.1
 
본격적인 프로젝트에 앞서 schema.prisma 모델 정의 합의는 정말 중요한 것 같다. (중간에 모델 정의가 바뀌면 힘들다.)

 ---  
 
### 8.2
 
Merge 소식이 있으면(내가 하거나, 남이 하거나) 항상 git pull upstream으로 최신 상태를 유지하자. ( 최신 상태가 반영되지 않은 상태에서 작업하면 충돌이 많다.)

 ---  
 
### 8.3
 
커밋은 작은 단위로 자주 하자.( 많은 양을 한번에 커밋하려고 하다보면 코드 리뷰도 어려워지고, 충돌이 났을 때 고치기도 힘들다.)

 ---  
 
### 8.4 
 
의존성 같은 개발 환경은 처음에 다 같이 맞추고 들어가는 게 편하다. 폴더 구조도.

 ---  
 
### 8.5
 
백엔드에서 API 개발 후 postman 같은 도구들을 활용해서 응답이 잘 되는지 확인하는 테스트가 성공하더라도, 프론트엔드와 연동했을 때 오류가 날 수 있다. 
(jest:단위테스트 하는 법은 아직 배우지 않아서 postman만 활용. 프론트엔드와 연동했을 때 오류가 나는 건 각각의 서버 터미널을 보면 어디 오류인지 확인할 수 있다.
예를 들어 백엔드 서버에서는 정상적으로 200 OK 응답 신호를 보냈는데, 프론트엔드 서버에서는 오류가 난다거나 하는 식으로. 이럴 경우 프론트엔드 코드를 고쳐야 하는데, 프론트엔드를 배우지 못했다보니 어찌해야 할지 난감하다. 그렇다고 백엔드 코드를 프론트엔드 코드에 맞게 수정하자니 백엔드 코드들은 잘 응답이 되었다는 점,  프론트엔드 폴더의 어느 부분을 참고해서 고쳐야 할 지 막막하다는 점이 힘든 것 같다.)

 ---  
 
### 8.6
 
커밋과 푸시는 신중히 ! (나중에 되돌리고 싶은 경우가 생기는데, 이 경우 상당히 복잡하다. git commit —amend를 쓰거나 git reset —soft HEAD~1, git revert <커밋해시> 등)

 ---  
 
### 8.7
 
PR 때 No conflicts with base branch라고 떠서 안심하고 Merge해도 나중에 오류가 날 수 있다.

---  

### 8.8
 
팀원들과의 소통이 굉장히 중요하다.

---  
 
### 8.9
 
공통으로 자주 쓰이는 함수나 변수 같은 경우는 utils 폴더를 만들어서 꺼내 쓰는 방법이 좋을 수 있다.

---  

### 8.10
 
PR을 날린 상황에서, 변경 사항이 생기면 PR을 닫지 않은 상태로도 커밋, 푸시하면 기록이 남는다.(여태 PR을 닫고 다시 새 PR을 날렸는데, 헛고생했다.)

---  

### 8.11
 
확인 작업은 차근차근 ! 
 
스키마 모델과 일치하는지
 
요구 사항과 부합하는지
 
API 명세서와 일치하는지
 
프론트엔드 코드들과 충돌은 일어나지 않는지

---  

### 8.12
 
swagger를 postman과 newman으로 자동 테스트를 진행하려면 전체 OpenAPI 문서를 하나의 파일로 합쳐야한다는 사실.
프로젝트 구조를 swagger 폴더에 swagger.js(info, title 내용 들어있는 부분) // Swagger/OpenAPI 문서를 JavaScript 객체로 조립하는 구조, openapi.yaml(summary 내용 들어있는 부분) 이렇게 두 파일로 나눴는데, 이렇게 나눠져있으면 Postman에서 못 읽는다.

---




