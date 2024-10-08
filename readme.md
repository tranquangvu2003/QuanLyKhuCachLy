<h1>Quarantine Area Management</h3>

[![tag](https://img.shields.io/badge/-quarantine%20area-FF888D)](https://github.com/MinhThinhrine?tab=repositories)
[![tag](https://img.shields.io/badge/-covid--19-FF888D)](https://github.com/MinhThinhrine?tab=repositories)
[![tag](https://img.shields.io/badge/-management-FF888D)](https://github.com/MinhThinhrine?tab=repositories)
[![os](https://img.shields.io/badge/-windows-EB8DCB)](https://github.com/MinhThinhrine?tab=repositories)
[![framework](https://img.shields.io/badge/-WPF-7C81E4)](https://github.com/MinhThinhrine?tab=repositories)
[![framework](https://img.shields.io/badge/-.NET%20Framework-7C81E4)](https://github.com/MinhThinhrine?tab=repositories)
[![framework](https://img.shields.io/badge/-C%23-7C81E4)](https://github.com/MinhThinhrine?tab=repositories)

[![school](https://img.shields.io/badge/school-HCMUAF-3f6cb6)](https://www.HCMUAF.edu.vn/)
[![subject](https://img.shields.io/badge/subject-OOAD-3f6cb6)](https://www.HCMUAF.edu.vn/)
[![contributors](https://img.shields.io/badge/contributors-4-1d9583)](#team)

<br>

<p align="center">
 <img src="./QuanLyKhuCachLy/Resources/logo/logo.png" alt="Quarantine Area Management logo" width = "450"></a>
</p>

<p align="center">
<i>The title means "<b>Quarantine Area Management</b>".</i>
<br/>
<i>This is a school project.</i>
</p>

<h3 align="center">Currently, the world are facing the Covid-19 pandemic and the need for quarantine areas has become very necessary. 🚩</h3>
<h3 align="center">Therefore, the management of the quarantine area needs to be done effectively and quickly in the context of an increasing number of people who need to be quarantined. 📈</h3>
<h3 align="center">The use of computer software to manage the quarantine area will help the work be done faster and more precisely. 📊</h3>

---

## 📝 Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
	- [Prerequisites](#prerequisites)
	- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
	- [Authentication](#authentication)
	- [Room Management](#room-management)
 	- [Person Management](#person-management)
 	- [Staff Management](#staff-management)
	- [Statistics](#statistics)
	- [Notification](#notification)
	- [Recommendation](#recommendation)
	- [Quarantine Area Setting](#quarantine-area-setting)
- [Tech Stack](#tech-stack)
- [References](#references)
	- [Libraries](#libraries)
	- [Resources](#resources)
- [Team](#team)
- [Contributing](#contributing)
- [Future Development](#future-development)
- [License](#license)

## Introduction

The quarantine area management system helps the operator to receive the quarantine area and helps the management process take place quickly and conveniently, satisfying the constraints of the quarantine business.

The quarantine area manages a large number of quarantined persons, rooms, and staff, along with facilities, information on test results, and the quarantined person's medical condition. The basic jobs that the quarantine area needs to manage are: managing information about the quarantine area, managing rooms, managing quarantined persons, managing staff, and reporting/statistics.

The quarantine area regularly receives a large number of quarantined people as well as processes a large amount of information. So we provide some features that help improve the jobs, such as updating the quarantined person list from excel, google sheets (information will be gathered from online forms that quarantined person input). We also provide an auto-recommend feature to suggest users execute the necessary actions based on existing data in the quarantine area. We also allow sending notifications to quarantined persons as well as managing notifications templates for the purpose of reusing. For more details, please see the [features](#features) section.

## Getting Started

### Prerequisites

This project uses [SQL Sever Express](https://www.microsoft.com/en-us/sql-server) as **Database Management System** and [.NET Framework](https://dotnet.microsoft.com/) (4.7.2 or higher).

* **SQL Sever Express** can be downloaded [here](https://go.microsoft.com/fwlink/?linkid=866658).
* **.NET Framework** can be downloaded [here](https://dotnet.microsoft.com/download/dotnet-framework).

Please make sure that your computer has these installed before continuing to the installation.

### Installation

1. Download **QLKCLInstallation.zip** file [here](https://github.com/MinhThinhrine?tab=repositories/releases/latest/download/QLKCLInstallation.zip) (latest version).
2. Extract the zip file.
3. Run **createdb.bat** file in **InitDB** folder.
4. Run **QLKCLSetup.msi** file in root folder to install.

## Usage
### Minimum system requirements:
* **OS:** Windows 10.
* **RAM:** 4GB.
* **Processor:** 1 GHz or faster processor or SoC.
* **Hard disk space:** 50 MB.

## Features

<br/>

<p align="center">
 <img src="./info/feature-introduction.png" alt="Quarantine Area Management Features"></a>
<i>Quarantine Area Management Features</i>
</p>

<br/>

### Authentication
* Users will be provided with an authenticated account to access the system. 
* Users can change the account’s password once the system is logged in.

<br/>

<p align="center">
 <img src="./info/ui/authentication.png" alt="Authentication UI"></a>
<i>Authentication UI</i>
</p>

<br/>

<p align="center">
 <img src="./info/ui/change-password.png" alt="Change Password UI"></a>
<i>Change Password UI</i>
</p>

<br/>

### Room Management
* Users can manage rooms with add (excel, manually)/edit/delete/clear/mark as completed room(s); search for/filter rooms; export room list.
* Users can also manage the room’s quarantined persons.

<br/>

<p align="center">
 <img src="./info/ui/room-list.png" alt="Room Management UI"></a>
<i>Room Management UI</i>
</p>

<br/>

<p align="center">
 <img src="./info/ui/room-detail.png" alt="Room Detail UI"></a>
<i>Room Detail UI</i>
</p>

<br/>

<p align="center">
 <img src="./info/ui/add-room-manually.png" alt="Add Room Manually UI"></a>
<i>Add Room Manually UI</i>
</p>

<br/>

<p align="center">
 <img src="./info/ui/edit-room.png" alt="Edit Room UI"></a>
<i>Edit Room UI</i>
</p>

<br/>

</p>
<p align="center">
 <img src="./info/ui/selection.png" alt="Selection UI"></a>
<i>Changing Room Severity Confirmation UI</i>
</p>

<br/>

</p>
<p align="center">
 <img src="./info/ui/person-in-room-update.png" alt="Update Person In Room UI"></a>
<i>Update Person In Room UI</i>
</p>

<br/>

### Person Management
* Users can manage persons with add (excel, from google sheets, manually)/edit/delete/mark as completed for the person(s); search for/filter persons; export person list. 
* Users can also change room for a specific person and update testing results based on excel.

<br/>


## Tech Stack

- **Languages:** [C#](https://docs.microsoft.com/en-us/dotnet/csharp/).
- **Database:** [SQL Server Express](https://www.microsoft.com/en-us/sql-server).
- **IDE:** [Visual Studio](https://visualstudio.microsoft.com/).
- **Version Control System:** [Git](https://git-scm.com/).
- **UI Prototype:** [Figma](https://www.figma.com/).
- **UI Framework:** [Windows Presentation Foundation (WPF)](https://docs.microsoft.com/en-us/visualstudio/designers/getting-started-with-wpf?view=vs-2022).

## References

### Libraries

#### Frontend

- [Material Design](https://github.com/MaterialDesignInXAML/MaterialDesignInXamlToolkit).
- [Live Chart](https://lvcharts.net/).
- [Font Awesome](https://www.nuget.org/packages/FontAwesome.WPF/).
- [Windows Presentation Foundation (WPF)](https://docs.microsoft.com/en-us/dotnet/desktop/wpf/overview/?view=netdesktop-6.0).

#### Backend

- [Entity Framework](https://docs.microsoft.com/en-us/ef/).
- [Google Sheets](https://developers.google.com/sheets/api).

### Resources

- [Google Fonts](https://fonts.google.com/):
	- [Noto Sans](https://fonts.google.com/noto/specimen/Noto+Sans?query=noto+sans).
- [Da Fonts](https://www.dafontfree.io/):
	- [Baloo](https://www.dafontfree.io/baloo-font/).

## Team

This project is contributed by **IT's Zoo team** consisting of 4 members:
- Đào Trung Tín *(Cá Mập)*: 21130556@st.hcmuaf.edu.vn
- Nguyễn Trường Thịnh *(mayditQN)*: 21130554@st.hcmuaf.edu.vn
- Trần Duy Tân *(ThichMinhTam)*: 21130531@st.hcmuaf.edu.vn
- Võ Minh Thịnh *(Darius)*: 21130549@st.hcmuaf.edu.vn

<br/>


*Made with [contrib.rocks](https://contrib.rocks).* </h4>

<br/>


## Contributing

Feel free to dive in! [Open an issue](https://github.com/MinhThinhrine?tab=repositories/issues/new).

1. Fork the Project.
2. Create your Feature Branch.

```sh
git checkout -b feature/super-feature
```

3. Commit your Changes.

```sh
git commit -m "Add super feature"
```

4. Push to the Branch.

```sh
git push origin feature/super-feature
```

5. Open a Pull Request.

## Future Development

### Quarantined Person's Interactive Interface
* This feature is aimed at users who are quarantined in the quarantine area. Here, on another platform (web), they can view information about the quarantine area, announcements as well as their personal information, test results, and they can also send requests, reports, complaints, requests for help, requests to change rooms, etc.

### Fee Management
* Users can manage the quarantine fees of quarantined persons.

<details>
<summary><b>More</b></summary>

In terms of future development, we will probably go deeper to perfect the advanced features as mentioned. For example, in the test result processing feature, we will go into more detail about the input variables for the test results (adding some data such as CT index, SPO2 concentration, breathing rate, etc.) so that the information can become more relevant to the outside business and make the processing of automatic recommendation features more complete and accurate; or we can also talk about the handling of the target group for the room and the quarantined person, here we can go into more detail about specifying the level of the target group, it can also be done by adding input variables as same as test results, this makes it possible to set rules on the target group level automatically instead of having to manually specify them. Moreover, detailing also helps to handle related features such as arranging rooms by level, suggesting to handle room change according to test results after processing the target group level for quarantined people.

In addition to diving into advanced features, we can also develop topics in the direction of expanding new features or even on new platforms. For example, a web-based application that allows quarantined people to monitor personal quarantine information, test results, notifications, quarantine information, etc. including allowing users to interact with the system such as sending requests, reports, complaints, requests for help, requests to change rooms, etc.

In addition to the main features directly related to the business, we may also develop additional features such as allowing selecting and customizing the interactive interface of the software; or develop the management of supplies, assets of the quarantine area, the management of factors about the needs of the quarantined person (such as wifi, food, drink, etc.), or maybe we will go deeper into the management of staff in the quarantine area.

</details>

<br/>

## License

```
MIT License

Copyright (c) 2021 IT's Zoo Team

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
