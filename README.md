# Fullstack_blogapp
This is a full stack blog site - application. 

# Basic Features

1. User has the ability to browse blog items
2. Blog item has a title, date and text
3. User has the ability to search blog items
4. User can add, delete and modify blog items

# Advanced Features

1. Commenting of blog items
2.	Long lists are using lazy loading or some other decent way. So if fetching all the blog items, the browser will not load them all at once

# Description
1. This app uses angular2+ front-end technology.
2. posts and comments data in json format are fetched from the server(backend) through angular services(provider) and 
   HttpClient.
3. Angular component(module) then subscribes from the angular services in order to retrieve and display the data to the browser in table 
   form.
4. The backend used were spring boot, jpa, hibernate, crudrepository, rest controller and mysql.

# Direction BackEnd
1. Download the backend file to your directory.
2. Go to src->main->resources folder and supply the required database url, username, password data of the apllication.properties file

spring.datasource.url=jdbc:"database url"
spring.datasource.username="yourusername"
spring.datasource.password="yourpassword"

3. Open command prompt and change directory to where you save the downloaded backend file.
4. Enter command

mvn compile

5. Then

mvn spring-boot:run

6. Then open another command prompt and enter command

mvn package

Note: Blog post api can be accessed at "http://localhost:8080/blogposts/"


# Direction FrontEnd

1. Install angular 2+ if you don't have yet in you computer.
2. Before installing angular make sure you have node and npm installed already also in your computer.  
3. Open command prompt (cmd) and enter this command:
   
   npm install -g @angular/cli
4. My project file is huge that I only uploaded here my src file. So still in command prompt create a new project directory by entering this command:
   
   ng new my-app
   
   Note: "my-app" is the project name.  You can name whatever you want.
5. Then go inside the file folder, by entering the command in the command prompt:

   cd my-app
 
6. Delete the src file of your newly created project.
7. Download the src file of this app and save it to your project to replace the deleted src file.

8 In your command prompt enter this command to start your app:

   ng serve –open
       
    
12. Project can be accessed at "http://localhost:4200/finalblogapp".

# License
LICENSE This program is a free software. Redistribution and/or modification is permitted under GNU General Public License v3.0 or any subsequent version.

This program is mainly for educational purposes and does not warrant its fitness for commercial game production capabilities.
# App screenshot home page
![Alt text](https://github.com/annviitala/fullstack_blogapp/blob/master/homepage.png?raw=true "Optional Title")
# App screenshot admin page
![Alt text](https://github.com/annviitala/fullstack_blogapp/blob/master/adminpage.png?raw=true "Optional Title")
# App screenshot comment page
![Alt text](https://github.com/annviitala/fullstack_blogapp/blob/master/commentpage.png?raw=true "Optional Title")




