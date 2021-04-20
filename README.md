# jamya
1. Visual studtio deeree folderoor нь neene :

    
    file->Open Folder-->lifenote
    
    

2.  Terminal gargaj ireed npm install gej bicne (NPM-ees module suulgah):

        Open Terminal-->npm i
    
    
3.  My Sql deer DataBase uusged (Mysql suulgasan baih ystoi):

    database uusgehdee eniig bicne 
       
        CREATE DATABASE IF NOT EXISTS nodelogin DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;
        USE nodelogin;

        CREATE TABLE IF NOT EXISTS blogPost (
          id int(11) NOT NULL,
          title varchar(50) NOT NULL,
           desTitle varchar(50) NOT NULL,
          description varchar(255) NOT NULL,
          blogPhoto varchar(255) NOT NULL,
           date varchar(255),
            user varchar(255) NOT NULL,
             category varchar(50)
        ) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;


        ALTER TABLE blogPost ADD PRIMARY KEY (id);
        ALTER TABLE blogPost MODIFY id int(11) NOT NULL AUTO_INCREMENT,AUTO_INCREMENT=2;
          CREATE TABLE IF NOT EXISTS accounts (
          id int(11) NOT NULL,
          username varchar(50) NOT NULL,
          password varchar(255) NOT NULL,
          email varchar(255) NOT NULL,
           profilePicture varchar(255)
        ) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;

        ALTER TABLE accounts ADD PRIMARY KEY (id);
        ALTER TABLE accounts MODIFY id int(11) NOT NULL AUTO_INCREMENT,AUTO_INCREMENT=2;     
         Бичээд run дархад болно
         
         
4.Visual studio ороод ".env" file uusgeed door baigaa code iig bicne
       (DB_PASSWORD deer uuriihuu password aa hiine)
   
            DB_HOST  = 'localhost'
            DB_USERNAME  = 'root'
            DB_PASSWORD = ''
            DB_NAME = 'nodelogin'
            SERVER_PORT = 3000
                      
5. hervee password cn too baival eniig hiine

           ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'uurihu passa hiine '
           
6. terminal gargaad 
        
        npm i gj bicne bas npm start gj bicne 
        
7.  odoo  browseroo gargaaad "Localhost:3000" гэж бичнэ


