[![Build Status](https://ci.suprizeapp.com/buildStatus/icon?job=Admin-Deploy-to-Dev)](https://ci.suprizeapp.com/view/Dev/job/Admin-Deploy-to-Dev/)

# Suprize Admin

# Installations
  install visual studio code  <br/>
  install rails  <br/>
  install ruby  <br/>
  install postgresql  <br/>
  install "imagemagick"  <br/>

# Database Schema Migration
  First create database  <br/>
  ```rails db:create```  <br/>
  After that migrate db  <br/>
  ```rails db:migrate```  <br/>
  For incremental db schema changes you need to add migrations  <br/>
  ``` rails db:migrate migration_name ```  <br/>
  then you can write you code to change the schema in this migration  <br/>
  And again run  <br/>
  ```rails db:migrate```  <br/>



# Configrations
  create .env file  <br/>
  copy the variables from ``` .env_sample ``` file and paste it in ``` .env ``` file  <br/>
  Replace all the values with your values  <br/>

# Running
  ```bundle install```  <br/>
  ```rails s```  <br/>
