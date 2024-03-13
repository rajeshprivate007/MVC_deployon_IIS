
# Deploy MVC application on IIS Server

This repository is for deploy a dotnet MVC project into IIS.


## Setup Guide

* Install IIS on your machine. (On windows feature on and off option enable IIS and required dot net version) and verify the IIS with local IP.

* Create a MVC application on Visual Studio and publish it to a directory/folder.

* Create an application pool and site on IIS. (provide the physical path of publishing folder)

* Now add the binding as a custom DNS. (example: abc.com)

* Add the custom DNS in hosts file with local IP (127.0.0.1)

* Now when user will browse the custom domain it will show the MVC application.
    