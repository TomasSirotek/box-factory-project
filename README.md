
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Box Factory Full stack 📦</h3>

  <p align="center">
    Compulsory assignment | Systems development
    <br />
    <br />
    <a href="https://frontend-phi-ten-59.vercel.app/dashboard">View demo</a>
    ·
    <a href="https://github.com/TomasSirotek/box-factory-project/issues">Report Bug</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>  
  <ol>
    <li><a href="#screenshot-of-the-project-features">Screenshots of the main page features</a></li>
     <li><a href="#deployement">Deployment</a>
    <ul>
        <li><a href="#front-end">Front end</a></li>
        <li><a href="#back-end">Back end</a></li>
        <li><a href="#database">Database</a></li>
      </ul>
    </li>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#repos">Repos</a></li>
      </ul>
    </li> 
    <li><a href="#build-with">Tech stack</a></li>
    <li><a href="#strict-minimal-requirements"> Strict minimal requirements</a></li>
    <li><a href="#extra-requirements"> Extra requirements</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

## Screenshots of the project features

### Main Dashboard page

#### Light mode dark mode
<div style="display: flex;">
  <img width="750" alt="Screenshot 1" src="https://github.com/TomasSirotek/box-factory-project/assets/72190589/ae431fac-6cf7-4470-83fd-91f81136089d">
  <img width="750" alt="Screenshot 1" src="https://github.com/TomasSirotek/box-factory-project/assets/72190589/1c2bf0ee-5505-434e-9a93-ad0d6080143f">
</div>

### Box Management page

#### Box data table | Search | Sort | Pagination
<div style="display: flex;">
  <img width="750" alt="Screenshot 1" src="https://github.com/TomasSirotek/box-factory-project/assets/72190589/8203a8da-bd54-4c1b-b36d-a1b860694edf">
  <img width="750" alt="Screenshot 1" src="https://github.com/TomasSirotek/box-factory-project/assets/72190589/1a2f60f6-71fb-4bfa-8989-d02a09d1ca5c">
</div>

#### Create box modal | Validation | Error handling
<div style="display: flex;">
  <img width="750" alt="Screenshot 1" src="https://github.com/TomasSirotek/box-factory-project/assets/72190589/69ecb624-fe36-46de-b3f7-fab966552f7a">
  <img width="750" alt="Screenshot 1" src="https://github.com/TomasSirotek/box-factory-project/assets/72190589/cbfe6b6b-363d-4433-91c1-01435c112a35">
</div>

#### Box page (ID) | Delete box | Update box | Validation | Error handling | Expandable Navbar
<div style="display: flex;">
  <img width="750" alt="Screenshot 1" src="https://github.com/TomasSirotek/box-factory-project/assets/72190589/3e3b9b72-431c-41e3-a0f9-4d7610554fbe">
  <img width="750" alt="Screenshot 1" src="https://github.com/TomasSirotek/box-factory-project/assets/72190589/1eb292b0-1bf1-4b6c-8941-54bf610ff458">
</div>

#### Extra info on the Apex chart | Sales data | Past orders 
<div style="display: flex;">
  <img width="750" alt="Screenshot 1" src="https://github.com/TomasSirotek/box-factory-project/assets/72190589/3e3b9b72-431c-41e3-a0f9-4d7610554fbe">
 
</div>

## Deployment 
------

You can go and run the app locally or visit the demo version of the app which is deployed on Azure and Vercel.
Frontend was deployed to Vercel in two stages (preview and production) where preview was on development branch and production on master branch.

Backend was tested locally and finally deployed to Azure Web App.

#### Front end 
* [Vercel](https://vercel.com)
Fully deployed via Git Actions to Vercel 

➡️ Visit View demo || https://frontend-phi-ten-59.vercel.app/management/boxes

#### Back end 
* [Azure](https://azure.microsoft.com/en-us/)
* [AzureWebApp](https://azure.microsoft.com/en-us/services/app-service/web/)
Fully deployed via Git Actions to Azure Web App

➡️ Visit View demo || https://box-factory.azurewebsites.net/api/boxes

<!-- ABOUT THE PROJECT -->
## About The Project
------

<div>
  <img width="700" alt="Screenshot 1" src="https://github.com/TomasSirotek/box-factory-project/assets/72190589/459c7d25-6b7e-446c-8662-d8156d5874d1">
  <br></br>
</div>

The boomer boss of the box factory wants to modernise by having an inhouse application to keep track of their products (boxes).

He wants employees to be able to add new boxes to their catalogue, edit existing, remove and find particular boxes based on searching and sorting preferences.

You, as the CTO, must decide what properties boxes have in the IT system. (In other words, there's no prebuilt database schema or starter app foundation to rely on)

### Built With (Tech stack)
------

#### Front end
* [Angular](https://angular.io)
* [Tailwind](https://tailwindcss.com)
* [Typescript](https://www.typescriptlang.org)
* [HTML](https://html.com)
* [SCSS](https://sass-lang.com)
* [Playwright](https://playwright.dev) 
    * E2E testing
* [Jest](https://jestjs.io)
    * Unit testing

#### Back end 
* [Dotnet](https://dotnet.microsoft.com)
* [Rest API](https://restfulapi.net)
* [Playwright](https://playwright.dev)
* [NUnit](https://nunit.org)

#### Database 
* [ElephantSQL](https://www.elephantsql.com)

### Repos
------

#### Front end
- https://github.com/TomasSirotek/frontend

#### Back end 
- https://github.com/TomasSirotek/factory-backend


### Strict minimal requirements:
------

- The client application must be built using Angular. ✅

- The backend must be built using a .NET Web API + Relational Database. ✅

- Communication between client and server should be done using HTTP. ✅

- There must be data validation on both the client and server side. ✅

- There must be at least 1 business entity and 1 table in the database. ✅

There must be at least the following CRUD operations: ✅
 - Create a new box
 - Delete an existing box
 - Search boxes (Client side)
 - See all details for one given box on it's own page (get by ID)
 - Updating a box

- Any testing deemed relevant must be conducted in order to assure quality. This can be E2E testing using Playwright (SDK is free of choice, but I recommend .NET Playwright) or integration testing of API's (simply calling the API with an HTTP client in an NUnit test and making assertions). ✅

- You must have at least one workflow on Github Actions which automates building, running and testing of your application. ✅


### Extra requirements:
------
❗Optional hard feature ❗

The boomer boss also wants to keep track of orders. There must now be at least a box table, an order table and junction table. (1 order can have many box models and 1 box model can be on many orders, so this is a many-to-many relationship). ✅


⚠️Optional very hard feature⚠️

The boomer boss also wants visualisations of box sales from past orders. He likes to look at diagrams that show how many boxes are being sold over time, and wants you to use https://www.npmjs.com/package/apexcharts to visualise sales data coming from the API. ✅


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact


Tomas Sirotek - [@twitter](https://twitter.com/TomasSirotek_)- [@linkedIn](https://www.linkedin.com/in/tomas-sirotek/)


[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
