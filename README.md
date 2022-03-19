# Yoontube

## Implementation

### Users

- [x] User Authentication
- [x] Github Login
- [x] User Profile
- [x] Login
- [x] Logout

### Videos

- [x] Video Upload
- [x] Video Recording
- [x] Video Download
- [x] Search Video
- [x] AJAX Comments
- [x] View Count

### Theory

- [x] MVC
- [x] Routing
- [x] Templates
- [x] Models
- [x] Relationships

---

## Update log

### 2021.09.02 - 2021.09.03

- Routes 설계
- Controller & Router 틀

### 2021.09.04 - 2021.09.05

- templates setup

### 2021.09.10

- GET/POST form Recap

### 2021.09.11

- Setting Mongo DB & Mongoose

### 2021.09.12

- Video Model

### 2021.09.19

- Home controller에 async 적용
- Video CRUD - Create

### 2021.09.20

- Video Detail
- Video CRUD - Update(Edit)

### 2021.09.21

- Video CRUD - Delete

### 2021.09.22

- Video CRUD - Read(Search)
- Create Account
- Form Validation with status codes

### 2021.09.24 - 2021.09.26

- cookie, session
- User Authentication

### 2022.01.25 ~ 2022.02.01

- Review all

### 2022.02.01 - 2022.02.02

- Github Login

### 2022.02.04

- Logout

### 2022.02.O5

- Edit Profile

### 2022.02.06

- Change Password

### 2022.02.07

- File Upload
- Static File Setting

### 2022.02.09

- Video Upload
- User Profile
- Relationships between User and Video
- Bugfix: Protect Edit Page, about "!==" operator

### 2022.02.10

- Webpack Configuration
- Configuraiton for detecting changes on FrontEnd

### 2022.02.11

- Styles
- Video/User Populate 적용: for Home, Detail View
- Video Player - play, pause

### 2022.02.12

- Video Player - volume, mute, current/duration time, timeline, fullscreen, controls
- Video Player - styles

### 2022.02.13

- View(조회수) Controller
- View(조회수) Event

### 2022.02.14 - 2022.02.15

- Comment(댓글)

### 2022.02.16

- Video metadata loading 지연으로 인한 bug fix
- Flash Messages
- Flash message, Logout시 session destroy 충돌 문제 해결(session.destroy -> null)
- Video edit 적용 안 되던 bug fix(controller에서 video exist -> findbyId)
- Comment 작성 안 되던 것과 관련된 bug 모두 fix -> [PACK] regenerator-runtime 설치

### 2022.02.24

- Handling other urls

### 2022.03.08

- Recording Video

### 2022.03.19

- Download Recorded Video
- Transcode Video
- Download Transcoded Video
