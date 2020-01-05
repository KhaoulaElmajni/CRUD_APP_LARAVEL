# <strong style="color:#fda50f; opacity: 0.80">CRUD IN LARAVEL & REACTJS</strong> :mortar_board:
## <span style="color:blue "> 1.Project Presentation</span>
* <strong style="color:dark">Our project is CRUD Application that any body can use it as a reminder of tasks that he should do, he can add or edit or delete a task or some thing to do.
* <strong style="color:dark">At first the user should register if he doesn't has an account or log in if he does, in case of forgeting password he can click on forget password to receive a new one in his owne email, after that he can get in his space to adding or editing or deleting tasks.
# <span style="color:green">2.Main Technologies Used</span>
 #### <span style="color:#0036ad"> 1.LARAVEL:</span>
 * <strong style="color:dark">Laravel is a web application framework with expressive, elegant syntax. We’ve already laid the foundation — freeing you to create without sweating the small things.
* <strong style="color:dark">Laravel, created by Taylor Otwel, initiates a new way of designing a framework using the best that exists for each feature. For example, any web application needs a system that handles HTTP requests. Rather than reinventing something, the designer of Laravel simply used that of Symfony by extending it to create an efficient routing system. Similarly, sending emails is done with the SwiftMailer library. In a way, Otwel has made its market among all the libraries available. We will see in this course how this is achieved. But Laravel is not only the regrouping of existing libraries, it is also many original components and above all an orchestration of all this.
*see also* [LARAVEL](https://laravel.com)
#### <span style="color:#0036ad"> 2.REACTJS:</span>
 * <strong style="color:dark">React is a library that only manages the application interface, considered as the view in the MVC model. It can thus be used with another library or an MVC framework like AngularJS. The library sets itself apart from its competitors by its flexibility and performance, by working with a virtual DOM and by updating the rendering in the browser only when necessary.
*see also* [REACTJS](https://fr.reactjs.org/)
#### <span style="color:#0036ad"> 3.NODEJS:</span>
 * <strong style="color:dark">Among the native modules of Node.js, there is http which allows the development of HTTP server. It is therefore possible to do without web servers such as Nginx or Apache when deploying websites and web applications developed with Node.js
*see also* [NODEJS](https://nodejs.org/en/)
#### <span style="color:#0036ad"> 4.NPM:</span>
 * <strong style="color:dark">npm is the official package manager of Node.js. Since version 0.6.3 of Node.js, npm is part of the environment and is therefore automatically installed by default3. npm works with a terminal and manages dependencies for an application. It also allows you to install Node.js applications available on the npm repository.
*see also* [NPM](https://www.npmjs.com/)
#### <span style="color:#0036ad"> 5.COMPOSER:</span>
 * <strong style="color:dark">Composer is free dependency manager software written in PHP. It allows its users to declare and install the libraries that the main project needs. The development started in April 2011 and gave rise to a first version released on March 1, 2012. Developed at the beginning by Nils Adermann and Jordi Boggiano 4 (which continue to maintain it today), the project is now available on the GitHub5 platform. It is thus developed by an entire community6.
Composer software is the initiator of a PHP port of Open Suse's Libzypp satsolver7 software.
The Composer software is strongly inspired by the npm software for Node.js and bundler8 for Ruby9.
*see also* [COMPOSER](https://getcomposer.org/)
 ## <span style="color:green ">3.CONCEPTION & ANALYSES</span>
 * ###### <strong style="color:red; opacity: 0.80">UML</strong>
 ![](https://i.imgur.com/MwrmPr2.png)
 > Use Case Diagramm [color=#fd837b]
  ---
 ## <strong style="color: green; opacity: 0.80" >4.HOW WE DID IT ?   </strong>
:::spoiler
installing composer
installing laravel
installing nodeJS
installing npm
create a project
:::

*for installing Laravel we run this commands*

  
```bash=
composer global require laravel/installer
composer create-project --prefer-dist laravel/laravel CRUDAPP
php artisan react preset 
php run dev
php run watch
php artisan serve
```
*for installing react we run this commands*
before it we should install [NODE.JS](https://nodejs.org/en/)
```bash=
npm install -g create-react-app
create-react-app new-app
cd new-app
npm start
```

 ## <strong style="color: green; opacity: 0.80" >5.how does it look ?</strong>
 
:::success
yeaaaah it's like that :white_check_mark: 
:::
![](https://i.imgur.com/CQAqr5q.png)
>Login form [color=#fd837b]

![](https://i.imgur.com/vbFhRwp.jpg)
>Register form [color=#fd837b]

![](https://i.imgur.com/0m47joy.jpg)
>Adding,editing,updating tasks form [color=#fd837b]

> Created by :[name=ELMAJNI KHAOULA IMANE LAHLOU]
[time=sun,2020,01,04][color=#EF0101]
