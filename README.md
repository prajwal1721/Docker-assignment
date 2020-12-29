#### Docker-assignment
#Docker assignment | Sem 5 

``Question :``
  
  Create a Docker-compose yaml for the following Multi-container app (Drupal postgres)

  contianer1 (front-end)  

  Front-end image - drupal:8-apache

  Container port - 80

  Volumes 
  
      - /var/www/html/modules

      - /var/www/html/profiles
    
      - /var/www/html/themes
    
      - /var/www/html/sites
  contianer2(database)

  Back-end image - postgres:10

  environment variable - POSTGRES_PASSWORD: example

  Note: Bring up both the containers on same user defined bridge network


## Screenshots:


![Screenshot1](https://github.com/prajwalsfs1721/Docker-assignment/blob/main/Images/Screenshot1.png)


![Screenshot2](https://github.com/prajwalsfs1721/Docker-assignment/blob/main/Images/Screenshot2.png)
