[![Build Status](https://ci.suprizeapp.com/buildStatus/icon?job=Admin-Deploy-to-Dev)](https://ci.suprizeapp.com/view/Dev/job/Admin-Deploy-to-Dev/)

# Suprize Admin

# Installations
  install visual studio code  
  install rails  
  install ruby  
  install postgresql  
  install "imagemagick"  

# Database Schema Migration
  First create database  
  ```rails db:create```  
  After that migrate db  
  ```rails db:migrate```  
  For incremental db schema changes you need to add migrations  
  ``` rails db:migrate migration_name ```  
  then you can write you code to change the schema in this migration  
  And again run  
  ```rails db:migrate```  



# Configrations
  create .env file  
  copy the variables from ``` .env_sample ``` file and paste it in ``` .env ``` file  
  Replace all the values with your values  

# Running
  ```bundle install```  
  ```rails s```  
