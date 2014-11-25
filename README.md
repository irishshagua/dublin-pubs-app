dublin-pubs-app
===============

A view of all the pubs that me and Kev have drank in, in Dublin


The project architecture is shown below.
The datastore is a postgresql db. 
There is a JEE app sitting in front of this with a JPA ORM layer which exposes a JAX-RS rest interface.
There is a native android (built with cordova so can add ios and firefox os or whatever in the future) app built with andular JS and Onsen UI which utilises the REST service.
There *will* be a web app which will be built with bootstrap so that it is useable on both desktop and mobile.

![alt tag](https://raw.githubusercontent.com/irishshagua/dublin-pubs-app/master/architecture/AppArchitecture.png)