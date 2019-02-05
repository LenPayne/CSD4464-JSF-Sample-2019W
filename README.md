# CSD-4464 JavaServer Faces Sample for 2019W

This sample walks through a few basic examples of a JSF app with some logic.

This project was created by:

1. Creating a new Java Web Application project in NetBeans.
2. Creating a JSF Page and inserting some specific tags.
3. Creating a HelloWorldBean class that was @Named and @ApplicationScoped.
4. Creating a LoginBean class that was @SessionScoped and implemented doLogin.

NOTE: During development of complex web applications, the GlassFish server is 
known to have issues with redeployment. You may need to restart the GlassFish
server to remedy errors like "No active contexts for scope type 
javax.enterprise.context.SessionScoped". GlassFish can be restarted in the
NetBeans UI, or may be restarted simply by restarting NetBeans.