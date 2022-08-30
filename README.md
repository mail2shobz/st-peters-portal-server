[![Build Status](https://semaphoreci.com/api/v1/riginoommen/st-peters-portal-server/branches/master/badge.svg)](https://semaphoreci.com/riginoommen/st-peters-portal-server)

St Peters Marthoma Church Server Side for the Portal
========================================

Server-side configuration based upon Node JS.

Installation Instructions:
--------------------------

 1. Clone the repository: `git clone https://github.com/riginoommen/st-peters-portal-server.git`
 2. Install the dependencies: `npm install`
 
 * _if you are using linux install dependencies 'sudo npm install'_  

Usage:
------

 * To start the application server: `npm start`
 * Default port being 5000, point browser to localhost:5000 to view the running application. 

Podman Installation Instructions:
-------------------------
1. Install podman package as mentioned in the installation guide depending on your OS : `https://podman.io/getting-started/installation`  
2. Clone the repository: `git clone https://github.com/riginoommen/st-peters-portal-server.git`

Usage:
------
  * To build the application via podman (from the source file): `podman build -t st-peters-portal-server .`
  * To start the application : podman run -ti -p 5000:5000 -d st-peters-portal-server`
