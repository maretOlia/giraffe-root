GIRAFFE
==========

'Task tracker' is server-side application for private(not work related) task management. 
Written in Java and based on Spring Boot/Data/OAuth2/HATEOAS and uses MySql DB as storage 

Simple 'playground' project to explore new technologies and libraries. 
____________________________________________________________________________________________________________________________

Project currently consist of 3 parts:

- 'tracker' 

As a Resource server current module responsible for task and user information manipulation and storage;

- 'auth'

Custom AOuth2 Authentication server that provides JWT Tokens as authentication/authorization mean. Also supports SSO, 
exchanging obtained tokens from external Auth Servers for custom JWT Tokens;

- 'shared' 

Holds Beans and Configuration classes shared between two previous modules.
____________________________________________________________________________________________________________________________


