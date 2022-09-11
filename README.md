# Aevapay

**Readme before launch app to facilitate the operation**
- Download Docker.rar and extract
- change the host of mysql in **.env** file in aevapay folder to your local ip address ex: **DB_HOST=192.168.1.11**
- Inside docker folder you extracted RUN your powershell as administrator
- Type just this command :
  **docker-compose up**
  and Wait until -:
  - Mysql container run (auto create root user with blank password and db with name aevapay) 
  - auto settings configured  - including setting of permissions
  - Auto Migration
  - Task runner triggered
  - Apache restart automatically 
  **these sequence may take a lot of time depend on your machine till images and containers be ready**
  Now you can access **Aevapay project** to make sure it's run through **http:localhost/public**
  If you would like to view an overview of **scheduled tasks** and the next time they are scheduled to run, you may use the schedule:list Artisan command:
    **php artisan schedule:list**
    
  **  MAHMOUD EL BOSHY **
  
