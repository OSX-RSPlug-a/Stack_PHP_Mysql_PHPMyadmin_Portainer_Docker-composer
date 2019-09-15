# Stack_PHP_Mysql_PHPMyadmin_Portainer_Docker-composer

  Docker-composer script stack Php development

To init this project:

  1 - Create a tree folder: 
  
    - proj_folder
        - dump
        - session
        - www
  
  2 - Create a file with name Dockerfile with no extension. It's where your php server will receive the instructions to add versions or install adds;
  
  3 - Run command:
  
    docker-compose -f THENAME.yaml up	-d
    
 So there are 4 containers on ports:
 
   - localhost:9000 (Composer to administrate your containers on browser);
   
   - 0.0.0.0:8001 (PHP server and the files to work on the folder www);
   
   - 0.0.0.0:8000 (PHPMyadmin to administrate your Mysql server);
   
   - 0.0.0.0:3306 (Mysql server);
   
   
   
  
  
