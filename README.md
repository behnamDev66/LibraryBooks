# LibraryBooks
renting books and managing library, and sending mail to users who rent books..
.....................
1- change hibernate.properties in resources folder for connecting to your database
2- make a database with name web_library in your db (mysql for example)
3- for using java mail sender and avoiding from an exception after registering users, make the below changes:
    a -- change your email setting in security (enable 2 step verification and 16 digit password app)
    b -- set your email username and password in AppConfig in config package.
    c -- set your email address, your subject, your title (that you want to send for borrowers) and scheduler delay time in                SimpleScheduler file.
4- in the project structure set spring facets and add the following context files:
    a -- AppConfig
    b -- SecurityConfig
    c -- HibernateConfig
5- run project with a tomcat locally server...
6- enjoy it...
