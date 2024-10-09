# <span id="top"> Flownary </span>
<img width="840" height="600" src="https://github.com/JuyoungKwak0618/FlownaryReact/assets/155405909/bdfe39bb-3b23-421b-a3b2-4e11cc912a61">

# 소개 및 개요

프로젝트 기간: 2024-04-16 ~ 2024-06-14<br/>
인원: 6인 (FE 4, BE 1, DB 1)<br/>
주제: SNS 사이트 만들기<br/>
사용 언어: JS (React)<br/>
<details>
      <summary>프로젝트 구조 보기</summary>
    
```bash
📦 
 src
   ├─ App.js
   ├─ Proxy.js
   ├─ _mock
   │  └─ user.js
   ├─ api
   │  ├─ LocalStorage.js
   │  ├─ alert.css
   │  ├─ alert.jsx
   │  ├─ authHandlers.js
   │  ├─ axiosGet.js
   │  ├─ axiosPost.js
   │  ├─ customHook.jsx
   │  ├─ emptyCheck.js
   │  ├─ firebase.js
   │  ├─ image.js
   │  ├─ loading.css
   │  ├─ loading.js
   │  ├─ queryHook.jsx
   │  ├─ userAvatar.js
   │  └─ webSocketContext.js
   ├─ assets
   │  ├─ theme-dark
   │  │  ├─ base
   │  │  │  ├─ borders.js
   │  │  │  ├─ boxShadows.js
   │  │  │  ├─ breakpoints.js
   │  │  │  ├─ colors.js
   │  │  │  ├─ globals.js
   │  │  │  └─ typography.js
   │  │  ├─ components
   │  │  │  ├─ appBar.js
   │  │  │  ├─ avatar.js
   │  │  │  ├─ breadcrumbs.js
   │  │  │  ├─ button
   │  │  │  │  ├─ contained.js
   │  │  │  │  ├─ index.js
   │  │  │  │  ├─ outlined.js
   │  │  │  │  ├─ root.js
   │  │  │  │  └─ text.js
   │  │  │  ├─ buttonBase.js
   │  │  │  ├─ card
   │  │  │  │  ├─ cardContent.js
   │  │  │  │  ├─ cardMedia.js
   │  │  │  │  └─ index.js
   │  │  │  ├─ container.js
   │  │  │  ├─ dialog
   │  │  │  │  ├─ dialogActions.js
   │  │  │  │  ├─ dialogContent.js
   │  │  │  │  ├─ dialogContentText.js
   │  │  │  │  ├─ dialogTitle.js
   │  │  │  │  └─ index.js
   │  │  │  ├─ divider.js
   │  │  │  ├─ form
   │  │  │  │  ├─ autocomplete.js
   │  │  │  │  ├─ checkbox.js
   │  │  │  │  ├─ formControlLabel.js
   │  │  │  │  ├─ formLabel.js
   │  │  │  │  ├─ input.js
   │  │  │  │  ├─ inputLabel.js
   │  │  │  │  ├─ inputOutlined.js
   │  │  │  │  ├─ radio.js
   │  │  │  │  ├─ select.js
   │  │  │  │  ├─ switchButton.js
   │  │  │  │  └─ textField.js
   │  │  │  ├─ icon.js
   │  │  │  ├─ iconButton.js
   │  │  │  ├─ linearProgress.js
   │  │  │  ├─ link.js
   │  │  │  ├─ list
   │  │  │  │  ├─ index.js
   │  │  │  │  ├─ listItem.js
   │  │  │  │  └─ listItemText.js
   │  │  │  ├─ menu
   │  │  │  │  ├─ index.js
   │  │  │  │  └─ menuItem.js
   │  │  │  ├─ popover.js
   │  │  │  ├─ sidenav.js
   │  │  │  ├─ slider.js
   │  │  │  ├─ stepper
   │  │  │  │  ├─ index.js
   │  │  │  │  ├─ step.js
   │  │  │  │  ├─ stepConnector.js
   │  │  │  │  ├─ stepIcon.js
   │  │  │  │  └─ stepLabel.js
   │  │  │  ├─ svgIcon.js
   │  │  │  ├─ table
   │  │  │  │  ├─ tableCell.js
   │  │  │  │  ├─ tableContainer.js
   │  │  │  │  └─ tableHead.js
   │  │  │  ├─ tabs
   │  │  │  │  ├─ index.js
   │  │  │  │  └─ tab.js
   │  │  │  └─ tooltip.js
   │  │  ├─ functions
   │  │  │  ├─ boxShadow.js
   │  │  │  ├─ gradientChartLine.js
   │  │  │  ├─ hexToRgb.js
   │  │  │  ├─ linearGradient.js
   │  │  │  ├─ pxToRem.js
   │  │  │  └─ rgba.js
   │  │  └─ index.js
   │  └─ theme
   │     ├─ base
   │     │  ├─ borders.js
   │     │  ├─ boxShadows.js
   │     │  ├─ breakpoints.js
   │     │  ├─ colors.js
   │     │  ├─ globals.js
   │     │  └─ typography.js
   │     ├─ components
   │     │  ├─ appBar.js
   │     │  ├─ avatar.js
   │     │  ├─ breadcrumbs.js
   │     │  ├─ button
   │     │  │  ├─ contained.js
   │     │  │  ├─ index.js
   │     │  │  ├─ outlined.js
   │     │  │  ├─ root.js
   │     │  │  └─ text.js
   │     │  ├─ buttonBase.js
   │     │  ├─ card
   │     │  │  ├─ cardContent.js
   │     │  │  ├─ cardMedia.js
   │     │  │  └─ index.js
   │     │  ├─ container.js
   │     │  ├─ dialog
   │     │  │  ├─ dialogActions.js
   │     │  │  ├─ dialogContent.js
   │     │  │  ├─ dialogContentText.js
   │     │  │  ├─ dialogTitle.js
   │     │  │  └─ index.js
   │     │  ├─ divider.js
   │     │  ├─ flatpickr.js
   │     │  ├─ form
   │     │  │  ├─ autocomplete.js
   │     │  │  ├─ checkbox.js
   │     │  │  ├─ formControlLabel.js
   │     │  │  ├─ formLabel.js
   │     │  │  ├─ input.js
   │     │  │  ├─ inputLabel.js
   │     │  │  ├─ inputOutlined.js
   │     │  │  ├─ radio.js
   │     │  │  ├─ select.js
   │     │  │  ├─ switchButton.js
   │     │  │  └─ textField.js
   │     │  ├─ icon.js
   │     │  ├─ iconButton.js
   │     │  ├─ linearProgress.js
   │     │  ├─ link.js
   │     │  ├─ list
   │     │  │  ├─ index.js
   │     │  │  ├─ listItem.js
   │     │  │  └─ listItemText.js
   │     │  ├─ menu
   │     │  │  ├─ index.js
   │     │  │  └─ menuItem.js
   │     │  ├─ popover.js
   │     │  ├─ sidenav.js
   │     │  ├─ slider.js
   │     │  ├─ stepper
   │     │  │  ├─ index.js
   │     │  │  ├─ step.js
   │     │  │  ├─ stepConnector.js
   │     │  │  ├─ stepIcon.js
   │     │  │  └─ stepLabel.js
   │     │  ├─ svgIcon.js
   │     │  ├─ table
   │     │  │  ├─ tableCell.js
   │     │  │  ├─ tableContainer.js
   │     │  │  └─ tableHead.js
   │     │  ├─ tabs
   │     │  │  ├─ index.js
   │     │  │  └─ tab.js
   │     │  └─ tooltip.js
   │     ├─ functions
   │     │  ├─ boxShadow.js
   │     │  ├─ gradientChartLine.js
   │     │  ├─ hexToRgb.js
   │     │  ├─ linearGradient.js
   │     │  ├─ pxToRem.js
   │     │  └─ rgba.js
   │     └─ index.js
   ├─ components
   │  ├─ MDBox
   │  │  ├─ MDBoxRoot.js
   │  │  └─ index.js
   │  ├─ MDButton
   │  │  ├─ MDButtonRoot.js
   │  │  └─ index.js
   │  ├─ MDTypography
   │  │  ├─ MDTypographyRoot.js
   │  │  └─ index.js
   │  ├─ chart
   │  │  ├─ chart.js
   │  │  ├─ index.js
   │  │  └─ use-chart.js
   │  ├─ iconify
   │  │  ├─ iconify.jsx
   │  │  └─ index.js
   │  ├─ label
   │  │  ├─ index.js
   │  │  ├─ label.jsx
   │  │  └─ styles.js
   │  ├─ my-editor
   │  │  ├─ editorIndex.js
   │  │  ├─ media.jsx
   │  │  ├─ my-editor-switch.jsx
   │  │  ├─ my-editor.css
   │  │  └─ my-editor.jsx
   │  └─ scrollbar
   │     ├─ index.js
   │     ├─ scrollbar.jsx
   │     └─ styles.js
   ├─ context
   │  └─ index.js
   ├─ examples
   │  ├─ Breadcrumbs
   │  │  └─ index.js
   │  ├─ Charts
   │  │  ├─ BarCharts
   │  │  │  ├─ HorizontalBarChart
   │  │  │  │  ├─ configs
   │  │  │  │  │  └─ index.js
   │  │  │  │  └─ index.js
   │  │  │  ├─ ReportsBarChart
   │  │  │  │  ├─ configs
   │  │  │  │  │  └─ index.js
   │  │  │  │  └─ index.js
   │  │  │  └─ VerticalBarChart
   │  │  │     ├─ configs
   │  │  │     │  └─ index.js
   │  │  │     └─ index.js
   │  │  ├─ BubbleChart
   │  │  │  ├─ configs
   │  │  │  │  └─ index.js
   │  │  │  └─ index.js
   │  │  ├─ DoughnutCharts
   │  │  │  └─ DefaultDoughnutChart
   │  │  │     ├─ configs
   │  │  │     │  └─ index.js
   │  │  │     └─ index.js
   │  │  ├─ LineCharts
   │  │  │  ├─ DefaultLineChart
   │  │  │  │  ├─ configs
   │  │  │  │  │  └─ index.js
   │  │  │  │  └─ index.js
   │  │  │  ├─ GradientLineChart
   │  │  │  │  ├─ configs
   │  │  │  │  │  └─ index.js
   │  │  │  │  └─ index.js
   │  │  │  ├─ ProgressLineChart
   │  │  │  │  ├─ config
   │  │  │  │  │  └─ index.js
   │  │  │  │  └─ index.js
   │  │  │  └─ ReportsLineChart
   │  │  │     ├─ configs
   │  │  │     │  └─ index.js
   │  │  │     └─ index.js
   │  │  ├─ MixedChart
   │  │  │  ├─ configs
   │  │  │  │  └─ index.js
   │  │  │  └─ index.js
   │  │  ├─ PieChart
   │  │  │  ├─ configs
   │  │  │  │  └─ index.js
   │  │  │  └─ index.js
   │  │  ├─ PolarChart
   │  │  │  ├─ configs
   │  │  │  │  └─ index.js
   │  │  │  └─ index.js
   │  │  └─ RadarChart
   │  │     ├─ configs
   │  │     │  └─ index.js
   │  │     └─ index.js
   │  ├─ Configurator
   │  │  ├─ ConfiguratorRoot.js
   │  │  └─ index.js
   │  ├─ Footer
   │  │  └─ index.js
   │  ├─ Items
   │  │  └─ NotificationItem
   │  │     ├─ index.js
   │  │     └─ styles.js
   │  ├─ LayoutContainers
   │  │  └─ DashboardLayout
   │  │     └─ index.js
   │  ├─ Navbars
   │  │  └─ DashboardNavbar
   │  │     ├─ index.js
   │  │     ├─ mapComponent.jsx
   │  │     └─ styles.js
   │  └─ Sidenav
   │     ├─ SidenavCollapse.js
   │     ├─ SidenavRoot.js
   │     ├─ index.js
   │     └─ styles
   │        ├─ color-test.css
   │        ├─ sidenav.js
   │        └─ sidenavCollapse.js
   ├─ hooks
   │  ├─ use-responsive.js
   │  └─ use-scroll-to-top.js
   ├─ index.js
   ├─ layouts
   │  ├─ Search
   │  │  ├─ SearchIndex.js
   │  │  └─ search
   │  │     ├─ MySearchList.jsx
   │  │     └─ search.css
   │  ├─ admin
   │  │  ├─ boardList
   │  │  │  ├─ AdminBoardList.js
   │  │  │  └─ boardListIndex.js
   │  │  ├─ statistics
   │  │  │  ├─ app-conversion-rates.jsx
   │  │  │  ├─ app-current-subject.jsx
   │  │  │  ├─ app-current-visits.jsx
   │  │  │  ├─ app-order-timeline.jsx
   │  │  │  ├─ app-tasks.jsx
   │  │  │  ├─ app-traffic-by-site.jsx
   │  │  │  ├─ app-website-visits.jsx
   │  │  │  ├─ app-widget-summary.jsx
   │  │  │  └─ statisticsIndex.js
   │  │  └─ userList
   │  │     ├─ AdminUserList.js
   │  │     ├─ table-empty-rows.jsx
   │  │     ├─ table-no-data.jsx
   │  │     ├─ user-table-head.jsx
   │  │     ├─ user-table-row.jsx
   │  │     ├─ user-table-toolbar.jsx
   │  │     ├─ userListIndex.js
   │  │     └─ utils.js
   │  ├─ album
   │  │  ├─ AlbumIndex.js
   │  │  └─ components
   │  │     ├─ showAlbumList
   │  │     │  ├─ album.css
   │  │     │  ├─ carousel.jsx
   │  │     │  └─ index.js
   │  │     └─ yearSelect
   │  │        └─ index.js
   │  ├─ authentication
   │  │  ├─ components
   │  │  │  ├─ BasicLayout
   │  │  │  │  └─ index.js
   │  │  │  ├─ CoverLayout
   │  │  │  │  └─ index.js
   │  │  │  └─ Footer
   │  │  │     └─ index.js
   │  │  ├─ logout.jsx
   │  │  ├─ reset-password
   │  │  │  └─ cover
   │  │  │     └─ index.js
   │  │  ├─ sign-in
   │  │  │  └─ LoginIndex.js
   │  │  ├─ sign-up
   │  │  │  ├─ RegisterIndex.js
   │  │  │  └─ SmsLogin.jsx
   │  │  └─ theme.css
   │  ├─ chatting
   │  │  ├─ ChattingIndex.js
   │  │  ├─ ChattingSide.js
   │  │  ├─ Chattinglist.js
   │  │  ├─ Chattingtemp.js
   │  │  ├─ components
   │  │  │  ├─ ChattingModal.jsx
   │  │  │  └─ chat.css
   │  │  └─ dummy.js
   │  ├─ family
   │  │  ├─ FamilyIndex.js
   │  │  └─ UserList.jsx
   │  ├─ follow
   │  │  └─ Follow.jsx
   │  ├─ home
   │  │  ├─ Board
   │  │  │  ├─ BoardDetail.jsx
   │  │  │  ├─ BoardJS.js
   │  │  │  ├─ BoardOne.jsx
   │  │  │  ├─ BoardUrl.jsx
   │  │  │  ├─ MypageIndex.js
   │  │  │  ├─ PostingModal.jsx
   │  │  │  ├─ ReReply.jsx
   │  │  │  ├─ Reply.jsx
   │  │  │  ├─ board.css
   │  │  │  ├─ ko.js
   │  │  │  ├─ posting.css
   │  │  │  └─ postingStyle.jsx
   │  │  ├─ HomeIndex.js
   │  │  ├─ Update
   │  │  │  ├─ UpdateIndex.js
   │  │  │  ├─ posting.css
   │  │  │  └─ postingStyle.jsx
   │  │  ├─ components
   │  │  │  └─ todoList
   │  │  │     └─ index.js
   │  │  ├─ posting.css
   │  │  ├─ postingStyle.jsx
   │  │  ├─ todoList
   │  │  │  └─ TodoListIndex.js
   │  │  ├─ weather.css
   │  │  └─ write
   │  │     ├─ index.js
   │  │     ├─ posting.css
   │  │     └─ postingStyle.jsx
   │  ├─ mypage
   │  │  ├─ FollowList.jsx
   │  │  ├─ FollowmeList.jsx
   │  │  ├─ MypageIndex.js
   │  │  └─ mypage.css
   │  ├─ notifications
   │  │  └─ NoticeIndex.js
   │  ├─ setting
   │  │  ├─ SettingIndex.js
   │  │  └─ components
   │  │     ├─ ProfileCard.jsx
   │  │     ├─ ProfileEdit.jsx
   │  │     ├─ ProfileSetting.css
   │  │     ├─ SettingBirth.jsx
   │  │     ├─ SettingCheckPwd.jsx
   │  │     ├─ SettingNickname.jsx
   │  │     ├─ SettingTel.jsx
   │  │     ├─ index.txt
   │  │     └─ setting.css
   │  └─ team
   │     └─ TeamIndex.js
   ├─ routes.js
   ├─ theme
   │  ├─ css.js
   │  ├─ custom-shadows.js
   │  ├─ index.jsx
   │  ├─ overrides.js
   │  ├─ palette.js
   │  ├─ shadows.js
   │  └─ typography.js
   └─ ut
      ├─ format-number.jsx
      ├─ format-time.jsx
      └─ userLogin-Service.jsx
```
©generated by [Project Tree Generator](https://woochanleee.github.io/project-tree-generator)
</details>

<h2>🌟팀원 소개🌟</h2>
<table>
    <tr>
        <td align="center" style="height: 250px">
            <img src="https://github.com/JuyoungKwak0618/FlownaryReact/assets/155405909/baaede75-c7b1-4af9-9839-fd6b0365961c" height="180" width="180">
            <br>
            <strong>👑 이병학</strong>
            <br>
        <strong>github: <a href="https://github.com/Tetrodomino">Tetrodomino</a></strong>
            <br>
            <div style="display: flex; align-items: center;">
    <img src="https://img.shields.io/badge/-Team%20Leader-yellow" style="margin-right: 10px;">
    <img src="https://img.shields.io/badge/BackEnd-404040">
 <div>
            <strong>BE 설계 및 구현</strong>
            <br>
            <p>백엔드 전체적인 개발을 책임 및 담당</p>
        </div>
</div>
        </td>
        <td align="center" style="height: 250px">
            <img src="https://github.com/JuyoungKwak0618/FlownaryReact/assets/155405909/5a5660a3-ac07-4c39-a792-944ee1edbd83" height="180" width="180">
            <br>
            <strong>💻 윤영준</strong>
            <br>
           <strong>github: <a href="https://github.com/yeoungjunyoon">yeoungjunyoon</a></strong>
            <br>
            <img src="https://img.shields.io/badge/DataBase-008000">
             <div style="display: flex; align-items: center;">
                 <strong>DB 설계</strong>
            <br>
            <p>데이터베이스 설계 및 관리를 담당</p>
        </div>
        </td>
        <td align="center" style="height: 250px">
            <img src="https://github.com/JuyoungKwak0618/FlownaryReact/assets/155405909/5eb5bde5-261d-4e4c-ba43-11c1d0c2de05" height="180" width="180">
            <br>
            <strong>✏️ 이윤주</strong>
            <br>
            <strong>github: <a href="https://github.com/raisedeveloper">raisedeveloper</a></strong>
            <br>
            <img src="https://img.shields.io/badge/-Work%20Management%20-f67280">
             <div style="display: flex; align-items: center;">
                 <strong>기획</strong>
            <br>
            <p>프로젝트 기획 및 관리를 담당</p>
        </div>
        </td>
    </tr>
    <tr>
        <td align="center" style="height: 250px">
            <img src="https://github.com/JuyoungKwak0618/FlownaryReact/assets/155405909/f15f0994-9331-4ce4-87b9-c83ce4d47ef1" height="180" width="180">
            <br>
            <strong>🎨 곽주영</strong>
            <br>
            <strong>github: <a href="https://github.com/JuyoungKwak0618">JuyoungKwak0618</a></strong>
            <br>
            <img src="https://img.shields.io/badge/FrontEnd-007acc">
            <div style="display: flex; align-items: center;">
                 <strong>FE 설계 및 구현</strong>
            <br>
            <p>프론트엔드 개발 및 최적화를<br> 담당</p>
            </div>
        </td>
        <td align="center" style="height: 250px">
            <img src="https://github.com/JuyoungKwak0618/FlownaryReact/assets/155405909/c3402f3d-4b2b-4200-a4fc-b6d2d4b7b9a6" height="180" width="180">
            <br>
            <strong>🎨 정성한</strong>
            <br>
           <strong>github: <a href="https://github.com/JeongSunghan">JeongSunghan</a></strong>
            <br>
            <img src="https://img.shields.io/badge/FrontEnd-007acc">
            <div style="display: flex; align-items: center;">
                 <strong>FE 구현 및 UI/UX</strong>
            <br>
            <p>프론트엔드 개발과 친화적인 UI/UX를 담당</p>
        </td>
        <td align="center" style="height: 250px">
            <img src="https://github.com/JuyoungKwak0618/FlownaryReact/assets/155405909/563dd1c4-4ecc-4aa2-a638-396107328e04" height="180" width="180">
            <br>
            <strong>🎨 안순현</strong>
            <br>
           <strong>github: <a href="https://github.com/SoonHyunAn">SoonHyunAn</a></strong>
            <br>
           <div style="display: flex; align-items: center;">
    <img src="https://img.shields.io/badge/FrontEnd-007acc" style="margin-right: 10px;">
    <img src="https://img.shields.io/badge/BackEnd-404040">
           <div style="margin-top: 10px;">
            <strong>FE/BE 설계 및 구현</strong>
            <br>
            <p>프론트/백엔드의 전반적인 개발 담당</p>
           </div>
        </div>
        </td>
    </tr>
</table>

## 프로젝트 기술 스택
### 🔧 백엔드 (Back-end)
- **스프링부트 (Spring Boot)**: RESTful API와 비즈니스 로직을 처리하는 서버 구축에 사용되었습니다.
<br><br>

### 🎨 프론트엔드 (Front-end)
- **리액트 (React)**: 사용자 인터페이스(UI) 및 클라이언트 측 로직을 구현하는 데 사용되었습니다.
<br><br>

### 💾 데이터베이스 (Databases)
- **Firebase**: 실시간 데이터베이스 및 사용자 인증 관리에 활용.
- **Cloudinary**: 이미지와 비디오 파일 저장 및 관리.
- **MySQL**: 주요 관계형 데이터베이스로 사용되었습니다.
<br><br>

### 🔌 외부 API (External APIs)
- **SweetAlert2**: 사용자 알림과 경고 메시지 모듈로 사용.
- **openWeather API**: 날씨 정보를 가져오는 데 사용되었습니다.
<br><br>

## 프로젝트 관리 도구

### 📅 일정 관리 (Schedule Management)
- **Notion**: 프로젝트 문서화 및 일정 관리에 사용.
- **Jira**: 애자일 방식으로 스프린트 및 이슈 관리를 수행.

### 📂 파일 관리 (File Management)
- **GoogleDrive**: 프로젝트 문서 및 자료 공유.
- **Github**: 소스 코드 버전 관리 및 협업에 사용.



---
## 1. 메인 화면 (Main Page)

### 메인 화면
![메인](https://github.com/user-attachments/assets/163c63f8-503a-4229-b488-18bc6870c0ba)

---


## 1. 관리자 기능 (Admin Features)

### 관리자 로그인
![관리자 로그인](https://github.com/user-attachments/assets/aacb74dc-06fc-4494-a41b-748938c3ac87)

### 관리자 홈
![어드민 홈](https://github.com/user-attachments/assets/45e7572f-32e7-41ea-93e1-f2d6c3bdca13)
![어드민 홈2](https://github.com/user-attachments/assets/a9feb7d3-ec1b-4287-94f9-731dfa847b19)

### 관리자 기능
![관리자 기능](https://github.com/user-attachments/assets/697d6592-3b99-4732-a0ef-43dfe7861ae6)

### 활성/비활성 유저 관리
![어드민 활성유저](https://github.com/user-attachments/assets/c056693f-31b8-45a5-a039-ab1aa0391c11)
![어드민 비활](https://github.com/user-attachments/assets/58d5c4b3-c475-4fea-b94f-7afd8bb65efd)

---

## 2. 사용자 인증 및 관리 (User Authentication & Management)

### 로그인
![로그인](https://github.com/user-attachments/assets/227c4b9f-72ab-447c-acf5-b3262772b36f)

### 회원가입
![회원가입](https://github.com/user-attachments/assets/d4ca1282-58c7-4f49-8da9-4b182f87fa52)

### 마이페이지
![마이페이지](https://github.com/user-attachments/assets/7a1e80e7-6ecd-4605-bbac-bf2afe5b3189)

---

## 3. 게시글 관리 (Post Management)

### 게시글 기능
![게시글 기능](https://github.com/user-attachments/assets/a6d4f393-0b09-48d5-8341-ba2893d7f06a)

### 게시글 목록
![게시글목록](https://github.com/user-attachments/assets/fe4c13ee-0424-46a8-9060-78556f9a0e54)

### 신고 게시글
![신고게시글](https://github.com/user-attachments/assets/cec29e13-fbb4-4d80-9eb7-3daf88df6e49)

---

## 4. 알림 기능 (Notifications)

### 알림
![알림](https://github.com/user-attachments/assets/67ed24e2-a3cf-412e-a8cb-6a8638ddd0d4)

---

## 5. 설정 기능 (Settings)

### 설정 기능
![설정 기능](https://github.com/user-attachments/assets/8d5e98e7-3a01-424b-8abe-b7e8142b1bfd)

---

## 6. 채팅 기능 (Chat)

### 채팅
![채팅](https://github.com/user-attachments/assets/cc83e4f2-8e66-4811-9aae-a0d70a2a2a26)

### 채팅 내용
![채팅내용](https://github.com/user-attachments/assets/c78dcb1a-8502-4d30-abab-e9dd88bf679a)

---

## 7. 투두 리스트 (To-Do List)

### 투두 리스트
![투두](https://github.com/user-attachments/assets/f8047086-a438-4234-8883-1963cce3c22b)
![투두2](https://github.com/user-attachments/assets/b6eea131-2aab-46e9-b704-3aba3aff9a1b)
![투두3](https://github.com/user-attachments/assets/959c1f03-fd31-4601-8403-cadbe5446974)

---

## 8. 팔로잉/팔로워 기능 (Following/Follower)

### 팔로잉/팔로워 기능
![팔로잉팔로워기능](https://github.com/user-attachments/assets/18911556-3a7f-4413-adde-666a15e2e673)

---
### 기타
1. 최상위 경로에 env.local로 특정 키 등의 정보 필요합니다. 필요한 정보는 아래와 같습니다
- Firebase : REACT_APP_FIREBASE_API_KEY, REACT_APP_FIREBASE_AUTH_DOMAIN, REACT_APP_FIREBASE_PROJECT_ID, REACT_APP_FIREBASE_STORAGE_BUCKET, REACT_APP_FIREBASE_MESSAGING_SEMDER_ID, REACT_APP_FIREBASE_APP_ID
- Cloudinary : REACT_APP_CLOUDINARY_CLOUD_NAME, REACT_APP_CLOUDINARY_UPLOAD_PRESET, REACT_APP_CLOUDINARY_URL
- React : REACT_APP_API_KEY
- Kakao : YOUR_KAKAO_REST_API_KEY (java key)
- GENERATE_SOURCEMAP
- websocket : REACT_APP_WEBSOCKET_URL
- REACT_APP_ADDRESS
2. Spring Boot와 연계하여 사용할 경우 서버의 IP에 대한 웹소켓 연결을 Proxy.js로 하는 것이 필요합니다
