<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/your_username/TRACE-System">
    <img src="Assets/logo.png" alt="TANN Logo" width="250" height="250">
  </a>

  <h3 align="center">TRACE System</h3>

  <p align="center">
    A Centralized Issuance and Management System for Spare Parts and Supply Materials
    <br />
    <br />
    <a href="https://github.com/your_username/TRACE-System"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://tann-trace.glitch.me/"> Demo </a>
    
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#features">Features</a></li>
    <li><a href="#System-Architecture">System Architecture</a></li>
    <li><a href="#Implementation-Highlights">Implementation Highlights</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

![TRACE System Screenshot](./Assets/loginSS.png)

TRACE is a centralized issuance and management system developed for TANN Philippines Inc., a leading manufacturer in aroma applications and industrial embossing located in Sto. Tomas, Batangas. The system was designed to replace their manual stock card and paper request slip processes with a digital solution that provides:

* Real-time inventory tracking
* Automated stock level monitoring
* Role-based access control
* Comprehensive reporting and analytics
* Streamlined request and issuance workflows

The system addresses critical pain points in TANN Philippines' previous manual processes, including:
- Vulnerability to human errors
- Delayed inventory updates
- Risk of unauthorized withdrawals
- Inefficient administrative processes

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Node.js][Node.js]][Node-url]
* [![Express][Express.js]][Express-url]
* [![MongoDB][MongoDB]][MongoDB-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]

**Development Team**
* Frontend Dev
  - Matanguihan, Avril Phoebe
  - Quimpan, Nichole
* Backend Dev
  - Iglipa, Ian Paolo

**Username and Passwords**
| Role          | Username            | Default Password     | Access Level    |
|---------------|---------------------|----------------------|-----------------|
| System Admin  | `admin`             | `adminpass`          | Full access     |
| Logistics     | `logistics`         | `logisticspass`      | Level 2 Access  |
| Sales         | `sales`             | `salespass`          | Level 1 Access  |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FEATURES -->
## Features

- **Comprehensive Dashboard**
  - Real-time inventory statistics and visualizations
  - Quick-view panels for understocked/overstocked items
  - Historical data analysis with date-range filters

- **Inventory Management**
  - Centralized tracking of office supplies and spare parts
  - Advanced search and category filtering
  - Automated stock level monitoring with alerts

- **Request & Issuance Workflow**
  - Digital request slips replacing paper forms
  - Approval workflow integration
  - Complete audit trail of all transactions

- **User & Access Control**
  - Role-based permissions (Admin, Staff, Requester)
  - Secure authentication with TANN branding
  - Activity logging for accountability

- **Reporting & Analytics**
  - Customizable reports on inventory movement
  - Export functionality for data analysis
  - Visual charts for trend identification

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SYSTEM ARCHITECTURE -->
## System Architecture

TRACE follows a modern three-tier architecture:

1. **Presentation Layer**
   - EJS (Embedded JavaScript) templating engine
   - Server-rendered HTML pages
   - Role-specific views and dashboards
   - Interactive data visualizations using Chart.js
   - Bootstrap-powered responsive design

2. **Application Layer**
   - Node.js/Express backend
   - RESTful API endpoints
   - Session-based authentication
   - Role-based authorization middleware

3. **Data Layer**
   - MongoDB Atlas cloud database
   - Document-based structure for inventory items
   - Mongoose ODM for data modeling
   - Secure data access patterns

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- IMPLEMENTATION DETAILS -->
## Implementation Highlights

### Inventory Management Module
- Real-time stock level updates
- QR-ready item identification system
- Supplier management integration

### Dashboard Analytics
- Interactive charts using Chart.js
- Customizable date ranges for reporting
- Quick-action panels for common tasks

### Security Features
- JWT-based authentication
- Role-based access control (RBAC)
- Password policy enforcement
- Session management

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

### Current Development
- [x] Core inventory management
- [x] User access control
- [x] Basic reporting and analytics


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

**TANN Philippines Inc.**  
First Philippine Industrial Park (FPIP)  
Sto. Tomas, Batangas, Philippines  

**Email**
* Tann Philippines | tannphilippines@tanngroup.com
* Contact us
  - Iglipa, Ian Paolo | ian.iglipa@gmail.com
  - Matanguihan, Avril Phoebe | avrilphoebematanguiham@gmail.com
  - Quimpan, Nichole | nicholequimpan@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

We would like to express our gratitude to:

- TANN Philippines management for their vision and support
- The FPIP community for fostering innovation
- <a href="https://github.com/othneildrew/Best-README-Template/tree/main"><strong>The Best README Template</strong></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com
[MongoDB-url]: https://www.mongodb.com/ 
[MongoDB]: https://img.shields.io/badge/MongoDB-FAF9F6?style=flat-square&logo=MongoDB&logoColor=%2347A248
[Express-url]: https://expressjs.com/
[Express.js]: https://img.shields.io/badge/Express.js-0e0000?style=flat-square&logo=Express&logoColor=%23FAF9F6
[Node.js]: https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white
[Node-url]: https://nodejs.org/en 
