# spring-oauth2-facebook-https

In section I have implement3e simple oauth2 example using spring boot. 

Using oauth you can delegate your authentation to third party solutions or social platform.

In this section I used facebook basic login 

I mostly followed below tutorial but it is out dated so I have fixed following mentions issues. 

[https://spring.io/guides/tutorials/spring-boot-oauth2/#_social_login_simple]

## To implement complete solution I implemented following additional steps. 

I register new key on fb with 8443 port

I enable https in this application as this is madatory requirement from facebook.

I handle too many redirect issue by excluding some basics urls.  

