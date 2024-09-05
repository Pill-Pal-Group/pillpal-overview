# PillPal - Overview

<a name="top">

<div align="center">
  <img width="20%" src="./res/pillpal-logo.png" alt="logo"/>
</div>

<details>
  <summary>Click to expand</summary>

- [Introduction](#introduction)
- [Context](#context)
- [Feature](#feature)
- [Tech Stack](#tech-stack)
- [System Overview](#system-overview)
- [Screen Overview](#screen-overview)
  - [Web Admin/Manager Application](#web-adminmanager-application)
  - [Mobile User Application](#mobile-user-application)
- [Contributors](#contributors)

</details>

## Introduction

PillPal is an application that helps users to search for information about drugs and support taking medications as prescribed. The application provides a lot of useful features to help users manage their medications taking effectively, as well as for managers to manage medicines information and users' data.

The application is built with the main following technologies:

- **Flutter** to build up the mobile application
- **ReactJS** to build up the web application
- **.NET** to create RESTful API supporting for both applications
- **SQL Server** and **Redis** as main and cache database respectively

<p align="right"><a href="#top">[back to top]</a></p>

## Context

<div align="center">
  <img width="90%" src="./res/pillpal-context.png" alt="pillpal-context"/>
  <p>Context Diagram</p>
</div>

<p align="right"><a href="#top">[back to top]</a></p>

## Feature

Web Admin/Manager Application:

- Admin Dashboard
- User Management
- Medicine-related Management
- Support adding Medicine from **Excel** file
- Package Management

Mobile User Application:

- User Authentication
- Search for Medicine Information
- Scan and create Prescription
- Create Medication Intake Schedule
- Integrate third-party payment gateway (ZaloPay)

<p align="right"><a href="#top">[back to top]</a></p>

## Tech Stack

<div align="center" name="source-control">
  <a href="https://git-scm.com"><img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="git"/></a>
  <a href="https://github.com"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="github"/></a>
  <a href="https://github.com/actions"><img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="github-actions"/></a>
</div>

<div align="center" name="mobile">
  <a href="https://flutter.dev"><img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="flutter"/></a>
  <a href="https://dart.dev"><img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="dart"/></a>
  <a href="https://www.android.com"><img src="https://img.shields.io/badge/Android-34A853?style=flat-square&logo=android&logoColor=white" alt="android"/></a>
  <a href="https://m3.material.io"><img src="https://img.shields.io/badge/Material%20Design-757575?style=flat-square&logo=materialdesign&logoColor=white" alt="material-desgin"/></a>
</div>

<div align="center" name="frontend">
  <a href="https://react.dev"><img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="react"/></a>
  <a href="https://redux.js.org"><img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white" alt="redux"/></a>
  <a href="https://yarnpkg.com/"><img src="https://img.shields.io/badge/Yarn-2C8EBB?style=flat-square&logo=yarn&logoColor=white" alt="yarn"/></a>
  <a href="https://tanstack.com"><img src="https://img.shields.io/badge/React%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white" alt="react-query"/></a>
  <a href="https://axios-http.com"><img src="https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white" alt="axios"/></a>
  <a href="https://ant.design"><img src="https://img.shields.io/badge/Ant%20Design-0170FE?style=flat-square&logo=antdesign&logoColor=white" alt="ant-design"/></a>
</div>

<div align="center" name="deployment">
  <a href="https://www.docker.com"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="docker"/></a>
  <a href="https://www.nginx.com"><img src="https://img.shields.io/badge/Nginx-269539?style=flat-square&logo=nginx&logoColor=white" alt="nginx"/></a>
  <a href="https://vercel.com"><img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="vercel"/></a>
  <a href="https://render.com"><img src="https://img.shields.io/badge/Render-000000?style=flat-square&logo=render&logoColor=white" alt="render"/></a>
  <a href="https://cloud.google.com"><img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white" alt="google-cloud"/></a>
  <a href="https://sonarcloud.io"><img src="https://img.shields.io/badge/SonarCloud-F3702A?style=flat-square&logo=sonarcloud&logoColor=white" alt="sonar"/></a>
  <a href="https://firebase.google.com"><img src="https://img.shields.io/badge/Firebase-ffca28?style=flat-square&logo=firebase&logoColor=black" alt="firebase"/></a>
</div>

<div align="center" name="backend">
  <a href="https://dotnet.microsoft.com"><img src="https://img.shields.io/badge/.NET%208.0-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="dotnet"/></a>
  <a href="https://www.nuget.org"><img src="https://img.shields.io/badge/NuGet-004880?style=flat-square&logo=nuget&logoColor=white" alt="nuget"/></a>
  <a href="https://www.microsoft.com/sql-server"><img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft%20sql%20server" alt="sqlserver"/></a>
  <a href="https://redis.io"><img src="https://img.shields.io/badge/Redis-%23DD0031.svg?&style=flat-square&logo=redis&logoColor=white" alt="redis"/></a>
  <a href="https://hangfire.io"><img src="https://img.shields.io/badge/Hangfire-2B4A7B?style=flat-square&logo=hexo&logoColor=white" alt="hangfire"/></a>
  <a href="https://swagger.io"><img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black" alt="swagger"/></a>
  <a href="https://www.openapis.org"><img src="https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white" alt="openapi"/></a>
  <a href="https://jwt.io"><img src="https://img.shields.io/badge/JSON%20Web%20Tokens-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="jwt"/></a>
</div>

<p align="right"><a href="#top">[back to top]</a></p>

## System Overview

<div align="center">
  <img width="90%" src="./res/system-architecture.png" alt="system-architecture"/>
  <p>System Architecture Design</p>
</div>

<p align="right"><a href="#top">[back to top]</a></p>

## Screen Overview

### Web Admin/Manager Application

<div align="center">
  <img width="90%" src="./res/web/web-login.png" alt="web-login"/>
  <p>Login Screen</p>
</div>
<br/>
<div align="center">
  <img width="45%" src="./res/web/admin-dashboard-monthly.png" alt="admin-dashboard-monthly"/>
  <img width="45%" src="./res/web/admin-dashboard-timestamp.png" alt="admin-dashboard-timestamp"/>
  <p>Admin Dashboard Screen</p>
</div>
<br/>
<div align="center">
  <img width="45%" src="./res/web/medicine-screen.png" alt="medicine-screen"/>
  <img width="45%" src="./res/web/medicine-detail-screen.png" alt="medicine-detail"/>
  <p>Medicine Management Screen</p>
</div>

### Mobile User Application

<div align="center">
  <img width="30%" src="./res/mobile/mobile-login.png" alt="mobile-login"/>
  <p>Login/Register Screen</p>
</div>
<br/>
<div align="center">
  <img width="30%" src="./res/mobile/mobile-medicine.png" alt="medicine-search"/>
  <img width="30%" src="./res/mobile/mobile-medicine-search.png" alt="medicine-search"/>
  <img width="30%" src="./res/mobile/mobile-medicine-detail.png" alt="medicine-detail"/>
  <p>Medicine Search Screen</p>
</div>
<br/>
<div align="center">
  <img width="30%" src="./res/mobile/mobile-scan-prescript.png" alt="mobile-scan-prescript"/>
  <img width="30%" src="./res/mobile/mobile-add-prescript.png" alt="mobile-add-prescript"/>
  <img width="30%" src="./res/mobile/mobile-remind.png" alt="mobile-remind"/>
  <p>Medicine Prescription Screen</p>
</div>
<br/>
<div align="center">
  <img width="30%" src="./res/mobile/mobile-purchase.png" alt="mobile-purchase"/>
  <img width="30%" src="./res/mobile/mobile-payment.png" alt="mobile-payment"/>
  <img width="30%" src="./res/mobile/mobile-customerinfo.png" alt="mobile-customerinfo"/>
  <p>Medicine Purchase Screen</p>
</div>

<p align="right"><a href="#top">[back to top]</a></p>

## Contributors

The project was supervised by Ms. Truong Thi My Ngoc and was developed by the following members:

- [Nguyen Hoang Chien](https://github.com/Coder-From-VN) - Mobile Developer
- [Nguyen Phan Phuoc Thang](https://github.com/NguyenPhanPhuocThang) - Frontend Developer **[Team Leader]**
- [Nguyen Truong Thanh](https://github.com/tnt-exe) - Backend Developer
- [Vo Trong Dat](https://github.com/Frontier68) - Frontend Developer

<p align="right"><a href="#top">[back to top]</a></p>
