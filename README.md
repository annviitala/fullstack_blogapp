# fullstack_blogapp
spring boot, jpa, angular 2
This is a blog application.  

# Description
1. This app uses angular2+ front-end technology.
2. posts and comments data in json format are fetched from the server(backend) through angular services(provider) and 
   HttpClient.
3. Angular component(module) then subscribes from the angular services in order to retrieve and display the data to the browser in table 
   form.
2. In the browser, the user enters values on the input field for latitude and longitude.
3. When add button is clicked, the values are showed on the table and map out to the google map with a marker.
4. Each row corresponding to the latitude and longitude values has a delete button also.
5. When delete button is clicked for a certain row, the entire row is remove from the table and the marker is also removed from the map.


# Direction

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

8. 

10. In your command prompt enter this command to start your app:

   ng serve –open
   
11. Open your api:
  
    java -jar blogapp-0.1.0.jar
    
    Note: Blog post api can be accessed at "http://localhost:8080/blogposts/"
12. Project can be accessed at "http://localhost:4200/finalblogapp".

# License
LICENSE This program is a free software. Redistribution and/or modification is permitted under GNU General Public License v3.0 or any subsequent version.

This program is mainly for educational purposes and does not warrant its fitness for commercial game production capabilities.

# App screenshot
![Alt text](https://github.com/annviitala/location-app/blob/master/app_screenhot.png?raw=true "Optional Title")




