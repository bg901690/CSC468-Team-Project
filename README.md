# CSC468-Team-Project
Cloud Computing project for CSC 468 @ WCU

1) WebUI

To Run:
In cloudlab ssh terminal:
\n$ docker build -t webui .
\n$ docker run -d -p 8080:80 webui
\n$ docker ps   // lists docker images so you can check to make sure it's running on designated port
In browser:
\nclnodevm056-1.clemson.cloudlab.us:8080   // reference the ssh command from cloudlab and your designated port

Development So Far:
- Edited Dockerfile to install Node version 12-slim

Future Development:
- Edit Dockerfile to install MySQL instead of redis
- Change out redis factors in webui files to MySQL


2) MySQL Database


3) Worker


4) Generator


5) Hasher
