# DockerComposeWordpress
DockerCompose for Wordpress using NGinx, SQL and PHP

Step 1: Add your wordpress files in src (delete the txt file)
Step 2: Run docker-compose build && docker-compose up
Step 3: Open your browser on http://localhost:8080

Potential issues:
Check information you are trying give in your WPconfig files and docker-compose.yml 
Things you need to know:
1. Name of your database
2. Name of your MySQL user
3. Password of your MySQL user

Also don't forget to import database inside your docker container.


If you have any issues feel free to contact me