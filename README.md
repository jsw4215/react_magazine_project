<h3 align="center"><b>항해99 주특기 2주차 React 프로젝트, Magazine</b></h3>

<h4 align="center">📆 2022.02.18 ~ 2022.02.23</h4>
<br>
<br>

## 📌 소개

|장석우|
|:----:|
|![Photo_JANG_SUKWOO](https://user-images.githubusercontent.com/55970155/154599100-0bf2e188-84ec-4f11-ab23-e061b533964a.jpg) |

<br>

<h3><b>🎞 배포 URL 🎞</b></h3>

[배포 URL 바로가기](https://reactweek2-1161e.web.app/login)

<h3><b>💻 Now Working On.. 💻</b></h3>

Apply Recoil to the Project.

---

<h3><b>🎫 프로젝트 소개 🎫</b></h3>
- "리액트, 팀프로젝트 매거진" <br>
- React, Redux, Firebase를 이용하여 매거진을 만들어보자!!
<br><br> 

---

<br>
<h3 align="center"><b>🛠 Tech Stack 🛠</b></h3>
<p align="center">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/materialui-232F3E?style=for-the-badge&logo=materialui&logoColor=white">
</br>
<img src="https://img.shields.io/badge/react-375BD2?style=for-the-badge&logo=react&logoColor=white">
<img src="https://img.shields.io/badge/redux-3CBDB1?style=for-the-badge&logo=redux&logoColor=white">
<img src="https://img.shields.io/badge/firebase-FFCC33?style=for-the-badge&logo=firebase&logoColor=white">
<img src="https://img.shields.io/badge/recoil-945DD6?style=for-the-badge&logo=recoil&logoColor=white">
</br>
<img src="https://img.shields.io/badge/reactrouterdom-375BD2?style=for-the-badge&logo=reactrouterdom&logoColor=white">
<img src="https://img.shields.io/badge/styledcomponents-181717?style=for-the-badge&logo=styledcomponents&logoColor=white">


<br><br>
<h3 align="center"><b>🏁 Getting Started 🏁</b></h3>
<pre>
<code>
~$ cd react_plus_class
~$ yarn add react-router-dom
~$ yarn add react-redux
~$ yarn add styled-components
~$ yarn add @mui/material @emotion/react @emotion/styled
~$ yarn start
</code>
</pre>

<br>
<h3 align="center"><b>📂 Project Directory Structure 📁</b></h3>
<pre>
<code>
src/
┣ components/
┃ ┣ atoms/
┃ ┃ ┗ LoginBox.js
┃ ┣ molecules/
┃ ┃ ┣ LoginContainer.js
┃ ┃ ┗ SignUpBox.js
┃ ┣ organism/
┃ ┃ ┗ SignUp.js
┃ ┣ Card.js
┃ ┣ CommentList.js
┃ ┣ CommentWrite.js
┃ ┣ Header.js
┃ ┣ NotiBadge.js
┃ ┗ Post.js
┣ elements/
┃ ┣ Button.js
┃ ┣ Grid.js
┃ ┣ Image.js
┃ ┣ index.js
┃ ┣ Input.js
┃ ┣ Spinner.js
┃ ┗ Text.js
┣ images/
┃ ┗ like.js
┣ pages/
┃ ┣ postTypes/
┃ ┃ ┗ PostTypes.js
┃ ┣ Login.js
┃ ┣ LoginPage.js
┃ ┣ LoginTemp.js
┃ ┣ Notification.js
┃ ┣ PostDetail.js
┃ ┣ PostList.js
┃ ┣ PostWrite.js
┃ ┣ Signup.js
┃ ┣ SignUpPage.js
┃ ┗ SignUpTemp.js
┣ redux/
┃ ┣ modules/
┃ ┃ ┣ comment.js
┃ ┃ ┣ image.js
┃ ┃ ┣ post.js
┃ ┃ ┗ user.js
┃ ┗ configureStore.js
┣ shared/
┃ ┣ App.css
┃ ┣ App.js
┃ ┣ common.js
┃ ┣ Cookie.js
┃ ┣ firebase.js
┃ ┣ InfinityScroll.js
┃ ┣ Permit.js
┃ ┣ Search.js
┃ ┗ Upload.js
┣ App.test.js
┣ index.css
┣ index.js
┣ reportWebVitals.js
┗ setupTests.js
</code>
</pre>
<br>
<br>


---


<br>
<h3 align="center"><b>📢 Main function 📢</b></h3>
<br>


---


<br>
<h4><b>📰 Main Page 📰</b></h4>

<table width="100%">
    <tr>
        <td width="50%"><img src="https://user-images.githubusercontent.com/55970155/155251199-671a7011-385b-40d1-8700-5a01f088952b.PNG" /></td>
        <td width="50%">
            <h5>메인 화면</h5>
            <ul>
                <li>리덕스를 이용하여 Firebase FireStore에 저장된 값 로드하기</li>
                <li>리액트 라우터 돔을 이용하여 페이지 라우팅</li>
                <li>데이터 사용성을 위한 무한스크롤 구현</li>
                <li>좋아요 기능 구현</li>
                <li>댓글 기능 구현</li>
            </ul>
        </td>
    </tr>
</table>


---

<br>


<h4><b>📰 Login Page 📰</b></h4>

<table width="100%">
    <tr>
        <td width="50%"><img src="https://user-images.githubusercontent.com/55970155/155251422-5f72b2b6-6289-41a4-97d7-2e80dadba51f.PNG" /></td>
        <td width="50%">
            <h5>로그인 화면</h5>
            <ul>
                <li>Material UI 로그인 템플릿 사용</li>
                <li>redux를 이용한 전역 데이터 관리</li>
                <li>firebase Auth를 이용한 유저 정보 관리</li>
            </ul>
        </td>
    </tr>
</table>


<h4><b>📰 Signup Page 📰</b></h4>

<table width="100%">
    <tr>
        <td width="50%"><img src="https://user-images.githubusercontent.com/55970155/155251495-d01e3363-6e30-4e1e-9485-ceeba206ee08.PNG" /></td>
        <td width="50%">
            <h5>회원가입 화면</h5>
            <ul>
                <li>Material UI 회원가입 템플릿 사용</li>
                <li>redux를 이용한 전역 데이터 관리</li>
                <li>firebase Auth를 이용한 유저 정보 관리</li>
            </ul>
        </td>
    </tr>
</table>



<h4><b>📰 Notification Page 📰</b></h4>

<table width="100%">
    <tr>
        <td width="50%"><img src="https://user-images.githubusercontent.com/55970155/155251526-64082579-4967-4364-a9b8-325bbe947f56.PNG" /></td>
        <td width="50%">
            <h5>알림 화면</h5>
            <ul>
                <li>Material UI Badge를 이용한 실시간 알림기능 구현</li>
                <li>알림 클릭시 해당 게시물로 이동 구현</li>
            </ul>
        </td>
    </tr>
</table>

<br><br>

---

<br><br>

<h3 align="center"><b>🏷 Firebase  🏷</b></h3>

#### User

|Actions|Params - to|Params - from|Role|
|:--:|:--:|:--:|:--:|
|SET_USER| {id, pw, pw_check, user_name} | - |회원가입|
|GET_USER| - | {id, pw, user_name} | 정보조회(미구현) |
|LOG_OUT| deleteCookie | - |로그아웃|

#### Post

|Actions|Params - to|Params - from|Role|
|:--:|:--:|:--:|:--:|
|GET_POST| {start, next, size} | {post_list, paging} |포스트 *단위별로 GET|
|SET_POST| {post_list, paging} | - |포스트 *단위별로 SET|
|ADD_POST| {post} | - | 포스트 추가 |
|EDIT_POST| {post_id, post} | - | 포스트 수정 |
|LOADING|  {is_loading} | - |로딩 구분|
|DELETE_POST| {post_id} | - | 포스트 삭제 |
|LIKE_POST| {post_id, _user_id, like_status} | {[like], like_cnt} |좋아요 기능 구현|

*무한스크롤 구현으로 인한 화면단위 : 3 post

#### Image

|Actions|Params - to|Params - from|Role|
|:--:|:--:|:--:|:--:|
|UPLOAD_IMAGE| {image_url} | {image_url} |Image URL 업로드|
|SET_PREVIEW| {preview} | {preview} |Image Preview SET|

#### Comment

|Actions|Params - to|Params - from|Role|
|:--:|:--:|:--:|:--:|
|SET_COMMENT| {post_id} | {comment_list} |댓글 불러오기|
|ADD_COMMENT| {post_id, comment} | - |댓글 생성|

<br><br>


---


<h3 align="center"><b>✏ Trouble Shooting ✏</b></h3>
<br>
<details>
    <summary>
        <b>이미지 불러오기</b>
    </summary>
    <br>해결 : 작성중..
</details>
<details>
    <summary>
        <b>무한스크롤</b>
    </summary>
    <br>해결 : 작성중..
</details>
<details>
    <summary>
        <b>실시간 댓글 알림 기능</b>
    </summary>
    <br>해결 : 작성중..
</details>
<details>
    <summary>
        <b>좋아요 기능</b>
    </summary>
    <br>해결 : 작성중..
</details>
<details>
    <summary>
        <b>material UI </b>
    </summary>
    <br>해결 : 작성중..
</details>
