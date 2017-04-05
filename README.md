GIRAFFE
==========

Application for task planning, organizing and team collaboration.
____________________________________________________________________________________________________________________________

Application functionalities
____________________________________________________________________________________________________________________________

Basic:

- simple every-day time planning;

- task creation with simple description;

- task sharing through assignments between registered users.


PRO:

- 'projects' creation as the main unit for simple home-projects, small businesses and learning activities;

- task creation with detailed planning options;

- task sharing through assignments between registered users included as a 'virtual' team to project managed by admin

- task progress logging

- 'periods' creation within project scope for separating different stages of project development in a long run.


Planned functionalities:

- support for images, links and comments storage;

- support for 'location' mechanism attached to online maps service;

- productivity tracking for PRO functionalities;


____________________________________________________________________________________________________________________________

Technical characteristics
____________________________________________________________________________________________________________________________

 - Java based application with Spring Boot/Data JPA/OAuth2/ and MySql DB as storage engine;

 - supports on-site registration or Single Sign On through Facebook;


 The project currently consist of 3 parts:

 - 'tracker'

As a Resource server current module responsible for task and user information manipulation and storage;

- 'auth'

Custom AOuth2 Authentication server that provides JWT Tokens as authentication/authorization mean. Also supports SSO, 
exchanging obtained tokens from external Auth Servers for custom JWT Tokens;

- 'shared' 

Stores Beans and Configuration classes shared between two previous modules.
____________________________________________________________________________________________________________________________


