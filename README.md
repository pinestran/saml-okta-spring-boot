# saml-okta-spring-boot

This source is referenced from these sites:
* https://blog.joshsoftware.com/2020/04/22/single-sign-on-with-saml-and-spring-boot/
* https://github.com/Ashviniv/sso-okta-spring-boot

Special thanks to JOSH Team.

## SETUP and Connect Postgre SQL
* https://www.postgresqltutorial.com/install-postgresql/
* https://www.postgresqltutorial.com/connect-to-postgresql-database/

## sso-okta-spring-boot

This is the sample code used to run a spring boot application with SSO authentication.
To run this project, use following commands:

* 1.Install java 8 or above
* 2.Run command in command line mvn spring-boot:run or run this application in eclipse/Intellij as a java application.
* 3.Application will start on 8443 port. Now,open https://localhost:8443 from browser.
* 4.It will redirect to okta login page.
* 5.Use following credentials to login email: vibhute.ashvini4@gmail.com password: @shVini4
* 6.After successful authentication, it will be redirected to root(/) path, which will render user JSON.
