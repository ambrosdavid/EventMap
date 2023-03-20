<div id="top"></div>

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<div align="center">
    <img src="imgs/image.png" alt="Logo" width="100px" object-fit="cover">

  <h1 align="center">EventMap</h1>
  <h3 align="center">www.eventmap.it</h3>
  <h4>
(03/2023) Please note that the project is still in the works, currently in its final testing stage, so it is publicly visible but nobody is allowed to create an account and perform mutation actions.
</h4>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project


![Product Name Screen Shot][product-screenshot]
<div align="center">
    <a href="#Schema">AWS Infrastructure</a> 
</div>

<div>
<h1>EventMap</h1>
<p>EventMap is a platform that allows users to create events or sponsor existing public events, providing a general map view of all events in the area. It also offers a built-in chat system that enables users to communicate and send messages related to each event.</p>
<p>Events expire by default after 24 hours, after which they will be removed from the map. We offer premium plans that allow users to upgrade their accounts, post more events, or make them last longer. These plans can be found in your private area and will remain deactivated until the website reaches stability.</p>
<p>Unfortunately, Google Maps API can become expensive if the website has many users. As a result, I may decide to shut down the map view each month once it reaches 28,000 map loads per month. Unfortunately, there are not many cheap solutions for displaying maps or tile providers.</p>
<p>The platform only offers one way to authenticate: Google SignIn. This means that you must have a Google account to create events and access the chat system, and to perform additional actions.</p>

</div>


<div>
<h1>AWS Infrastructure</h1>
<p>This project primarily relies on AWS infrastructure, with other APIs and services also utilized, such as Google Maps API, Google OAuth, MongoDB Atlas Serverless, and Paypal.</p>
<p>The purpose of this repository is to showcase a demo of the project's complete architecture and functionality. The entire project was built from scratch by me.</p>
<p>The code for this project is stored in private repositories. For more information on accessing it, please contact me directly.</p>

</div>


### Built With


* [Angular](https://angular.io/)
* [AWS CDK V2 IaaS in NodeJs](https://docs.aws.amazon.com/cdk/api/v2/)
* [MongoDB Serverless](https://www.mongodb.com/use-cases/serverless)
* [Paypal Developers](https://developer.paypal.com/home)
* [Google Maps API](https://developers.google.com/maps)
* [Iubenda](https://www.iubenda.com/en/)


## Demo

<div id="Schema"></div>

<div align="center">
    <h4> AWS Infrastructure schema:</h4>
    <img src="imgs/AWS_schema.jpg" style= "width:100%" alt=""/>
    <br>
    <h4> The map view:</h4>
    <img src="imgs/example.PNG" style= "width:100%" alt=""/>
    <br>
    <h4> The event creation form:</h4>
    <img src="imgs/example2.PNG" style= "width:100%" alt=""/>
    <br>
    <h4> Once you click on an event you will see:</h4>
    <img src="imgs/example3.PNG" style= "width:100%" alt=""/>
<br>
    
    
<p>(<a href="#top">back to top</a>)</p>
</div>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/david-ambros-07404a174/
[product-screenshot]: imgs/main_bg.png
