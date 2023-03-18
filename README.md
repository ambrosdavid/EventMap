<div id="top"></div>

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<div align="center">
    <img src="imgs/image.png" alt="Logo" width="100px" object-fit="cover">

  <h1 align="center">EventMap</h3>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project


![Product Name Screen Shot][product-screenshot]
<div align="center">
    <a href="#demo">Demo</a> 
</div>


EventMap is my first startup project.The purpose of this platform is to allow users to create events or to sponsor existing public events, and to have a general map view of all the events in the area. 
EventMap offers a built-in chat system that allows users to comunicate and to send messages related to each event.
I have always hated websites that would make you go trough many registration steps in order to create an account, so in EventMap there is only one way to authenticate for simplicity and for an easy User Experience, that is Google SignIn, so you must have a google account in order to create Events and access to the chat system.
Events expire by default after 24h, so after that time the event will be removed from the map.
The website has some premium plans for who wants to upgrade their account and be able to post more events, or make them last longer, you can find that in your private area. Those premium plans will remain deactivated until the website reaches a stability. 

Unfortunatelly GoogleMaps API gets expensive if the website has many users so I might decide to shut down the map view each month once it reaches 28000 maploads per month. Unfortunatelly there are not many cheap solutions to display a map or tile-providers.

Respectively for front-end and back-end the following tools have been used:
* __Front-end:__ The Angular 14 framework was used.
* __Infrastructure:__ AWS CDK V2 IaaS was used, in NodeJs.


This project mainly relies on an AWS infrastructure, other API and services are used, like Google Maps API, Google OAuth, MongoDB Atlas serverless and Paypal.
The purpose of this repository is to show a demo about how it works and the complete architecture of the project. 
The entire project was built from 0 by me.
The code is stored in private repositories, for more information please contact me.

### Built With


* [Angular](https://angular.io/)
* [AWS CDK](https://docs.aws.amazon.com/cdk/api/v2/)
* [MongoDB Serverless](https://www.mongodb.com/use-cases/serverless)
* [Paypal Developers](https://developer.paypal.com/home)
* [Google Maps API](https://developers.google.com/maps)
* [Iubenda](https://www.iubenda.com/en/)



## Demo

<div id="demo"></div>

<div align="center">
    <h4> Gym web app:</h4>
    <img src="images/demo.gif" alt="demo"/>
    <br>
    <h4> Object diagram:</h4>
    <img src="images/schemaAoggetti.png" style= "width:80%" alt="schemaAoggetti"/>
<br>
    <h4> ER diagram:</h4>
    <img src="images/Relazionale.PNG" style= "width:80%" alt="Relazionale"/>

    
<p>(<a href="#top">back to top</a>)</p>
</div>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/david-ambros-07404a174/
[product-screenshot]: imgs/main_bg.png
