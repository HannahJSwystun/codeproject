# codeproject
playframework mysql jasper report pdf xls html graphic charts security departments roles deadbolt authentication onetomany manytomany ebean jobs actors import data xls filters by data &amp; queries bootstrap

0- create schema codeproject;   -- Mysql
1- Unzip Project >> to run project:   SBT CLEAN RUN
2- Insert some authentications : Steve : login : sysadmin@gmail.com      password : sysadmin

insert into authorised_user (id,email,user_name,fullname,profession,password_hash,createdt,createby,moddt,modby,validated,language) 
	values 
(1,'sysadmin@sysadmin.com','sch','Steve CHALONER','Administrator','$2a$10$XiF4V/mwTxeF9Hyox80dXuXoCgkCDGb24lq/pVibXCsTVMYm3fzgS','2017-01-01','sch',null,null,'1','en');

4- Add image user once connected :  page Analystes >> in the end of line click on image then add yours...
5- create roles, departments, pages,   add roles to pages to users and department only to users
6- create samples and then you'll see security per department or per role ( DEADBOLT security )

7- unzip this files and put them in c:/temp...
https://drive.google.com/file/d/0B97fo89guk_nXzRUVlZMTldCYVE/view?usp=sharing


-> in the end you should get something like :

http://imgur.com/a/mDrRt
