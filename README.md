# <span id="top"> Flownary </span>
<img width="840" height="600" src="https://github.com/JuyoungKwak0618/FlownaryReact/assets/155405909/bdfe39bb-3b23-421b-a3b2-4e11cc912a61">

# 소개 및 개요

프로젝트 기간: 2024-04-16 ~ 2024-06-14<br/>
인원: 6인 (FE 4, BE 1, DB 1)<br/>
주제: SNS 사이트 만들기<br/>
사용 언어: JS (React)<br/>

# 프로젝트 구조 🏗️
```bash
📦 
├─ .gitignore
├─ .npmrc
├─ .prettierrc.json
├─ CHANGELOG.md
├─ ISSUE_TEMPLATE.md
├─ LICENSE.md
├─ README.md
├─ jsconfig.json
├─ package-lock.json
├─ package.json
├─ public
│  ├─ _mock
│  │  └─ user.js
│  ├─ apple-icon.png
│  ├─ bg-profile.jpeg
│  ├─ cat.jpg
│  ├─ chatting.png
│  ├─ eiffel.jpg
│  ├─ favicon.png
│  ├─ images
│  │  ├─ DarkLogo.png
│  │  ├─ HelloBlack.png
│  │  ├─ HelloLight.png
│  │  ├─ LightLogo.png
│  │  ├─ LightLogoXs.png
│  │  ├─ NotFound.png
│  │  ├─ bestTeamWork.png
│  │  ├─ company_intro_clear3.png
│  │  ├─ favicon.png
│  │  ├─ flowBlur.jpg
│  │  ├─ flowCity.jpg
│  │  ├─ flowLight.png
│  │  ├─ flowNary_intro_team.gif
│  │  ├─ flowNight.png
│  │  ├─ home-decor-1.jpg
│  │  ├─ home-decor-2.jpg
│  │  ├─ home-decor-3.jpg
│  │  ├─ home-decor-4.jpeg
│  │  ├─ icons
│  │  │  ├─ chatBot.png
│  │  │  ├─ flags
│  │  │  │  ├─ AU.png
│  │  │  │  ├─ BR.png
│  │  │  │  ├─ DE.png
│  │  │  │  ├─ GB.png
│  │  │  │  └─ US.png
│  │  │  ├─ google.png
│  │  │  ├─ light dark.png
│  │  │  ├─ live-chatbot.gif
│  │  │  ├─ mail.png
│  │  │  ├─ name.png
│  │  │  ├─ profile.png
│  │  │  ├─ pwd.png
│  │  │  └─ quote-left-icon.png
│  │  ├─ logo-ct-dark.png
│  │  ├─ logo-ct.png
│  │  ├─ marie.jpg
│  │  ├─ sea.avif
│  │  └─ teamimage
│  │     ├─ DarkLogo.png
│  │     ├─ beonghak.png
│  │     ├─ juyong.png
│  │     ├─ soonhyun.png
│  │     ├─ sunghan.png
│  │     ├─ yongjun.png
│  │     └─ yunju.png
│  ├─ index.html
│  ├─ manifest.json
│  ├─ robots.txt
│  ├─ team.png
│  └─ weather.png
└─ src
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
                 <strong>FE 구현 및 디자인</strong>
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


# [1] [프로젝트 개요]
본 프로젝트는 SNS 소셜 네트워크 플랫폼의 현재와 과거의 이용률을 분석하고, 4060세대의 활발한 SNS 활동을 반영하여, 전 세계의 다양한 연령층이 소통할 수 있는 최적의 플랫폼을 제공하는 것을 목표로 합니다. 특히 실버세대를 포함한 모든 세대에게 적합하고, 사용 편의성과 트렌디한 UI 디자인에 중점을 둔 서비스를 구현합니다.

# [2] 주요 기능들
## 기본 기능
<details>
  <summary><b>1. 홈</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <h3>홈</h3>
    <ul>
      <li>첫 로그인 시 보이는 홈 화면</li>
        ![메인](https://github.com/user-attachments/assets/163c63f8-503a-4229-b488-18bc6870c0ba)
  </ul>
  </div>
</details>

<details>
  <summary><b>2. 앨범</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <h3>홈</h3>
    <ul>
      <li>첫 로그인 시 보이는 홈 화면</li>
          <img src="" alt="">
  </ul>
  </div>
</details>

 <details>
  <summary><b>3. 날씨</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>내용</li>
          <img src="" alt="">        
  </ul>
  </div>  
</details>

 <details>
  <summary><b>4. To-Do List</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>내용</li>
          <img src="" alt="">        
  </ul>
  </div>  
</details>


## 유저 관련 기능
<details>
  <summary><b>1. 회원가입 및 로그인</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <h3>가입 및 로그인</h3>
    <ul>
      <li>Firebase Authentication을 사용하여 로그인 기능 구현</li>
          <img src="" alt="">
       <li>Firebase Authentication을 사용하여 회원가입 기능 구현</li>
          <img src="" alt="">
  </ul>
  </div>
</details>

 <details>
  <summary><b>2. 유저 마이페이지</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
      <li>유저 정보 저장 및 관리</li>
  <img src="" alt="">
  </ul>
  </div>
</details>     

 <details>
  <summary><b>3. 유저 설정</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
      <li>유저의 정보를 설정 할 수 있는 페이지 입니다.</li>
  <img src="" alt="">
  </ul>
  </div>
</details>     

 <details>
  <summary><b>4. 앨범</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>내용</li>
          <img src="" alt="">        
  </ul>
  </div>  
</details>

<details>
  <summary><b>5. 알림</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>내용</li>
          <img src="" alt="">        
  </ul>
  </div>  
</details>

## 채팅 관련 기능
 <details>
  <summary><b>1. 채팅</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>채팅방 목록 및 채팅 내용을 표시</li>
          <img src="" alt="">        
  </ul>
  </div>  
</details>

 <details>
  <summary><b>2. 임시 채팅</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>채팅방 목록 및 채팅 내용을 표시</li>
          <img src="" alt="">        
  </ul>
  </div>  
</details>

## 팔로잉/팔로워 기능
 <details>
  <summary><b>1. 패밀리</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>카카오톡 오픈 채팅과 비슷한 기능입니다.</li>      
          <img src="" alt="">        
  </ul>
  </div>  
</details>

 <details>
  <summary><b>2. 플로잉/플로우</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>타 SNS의 팔로우 / 파로잉 기능이며, 해당 페이지에서는 자신이 팔로잉 및 팔로우한 목록을 볼 수 있습니다.</li>
          <img src="" alt="">        
  </ul>
  </div>  
</details>


## 관리자 전용 기능
 <details>
  <summary><b>1. 통계</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>userList 와 boarList를 불러온 후 각각의 맞는 조건에 따라 표시</li>
          <img src="" alt="">        
  </ul>
  </div>  
</details>

 <details>
  <summary><b>2. 사용자 관리</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>userList를 불러옵니다</li>
          <img src="" alt="">             
  </ul>    
  </div>       
</details>

 <details>
  <summary><b>3. 게시물 관리</b> (👈 Click)</summary>
  <br>
  <div markdown="1">
    <ul>
        <li>boardList를 불러옵니다</li>
          <img src="" alt="">             
  </ul>    
  </div>       
</details>




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
