<!-- XAMP: For Linux and Android --->

<p align="center">
  <img src=".github/logo/xamp.png">
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/AdarshAddee/XAMP?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/AdarshAddee/XAMP?color=teal&style=for-the-badge">
  <img src="https://img.shields.io/github/issues/AdarshAddee/XAMP?color=red&style=for-the-badge">
  <img src="https://img.shields.io/badge/Version-v1.0-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/AdarshAddee/XAMP?style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Author-AdarshAddee-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Written%20In-Bash-darkcyan?style=flat-square">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FAdarshAddee%2FXAMP&title=Visitors&edge_flat=false"/></a>
</p>

<p align="center">
  <b>XAMP - Server For Android!!!</b>
</p>

##

# XAMP
XAMP is a begginer friendly server for android which host(s) localhost(s) on android devices. <b>New feature for LINUX available after some time (Working on it!).</b> You can use this tool to start local server on android. After successfully executing tool, Just open <b>localhost:8080</b> to see your web page which is hosted on local server. 

## Features
- Begginer Friendly
- Supports CLI and GUI Mode
- Supports Multiple Servers
  - PHP
  - Python
  - Mysql
  - Apache2
  - Nginx

## Installation 
These are the following commands which can be used to install XAMP Serevr in Android (Termux).
- Install step-by-step!
  ```
  apt update && apt upgrade -y
  ```
  ```
  apt install git -y
  ```
  ```
  git clone https://github.com/AdarshAddee/XAMP.git
  ```
  
- One Line Installion!
  ```
  apt update && apt upgrade -y && apt install git -y && git clone https://github.com/AdarshAddee/XAMP.git
  ```
  
## Execution
These are the commands which can be used to execute XAMP Serevr in Android (Termux).
```
cd XAMP
```
```
chmod +x xamp
```

## Modes
XAMP - Server Supports GUI & CLI Mode as Well!
- ### GUI Mode!
  XAMP - Server in GUI Mode can be started with:
  ```
  ./xamp
  ```
- ### CLI Mode!
  XAMP - Server  in CLI Mode have some arguments!
  ```
  ./xamp [args]
  ```
  
  Open xamp help page
  
  ```
  ./xammp -h
  ```
  
  Here are some commands which can be used:
  ```
  usage: xamp [args]
  
  args:
    -h, --help            show help and exit
    -b, --banner          show banner and exit
    -py, --pyserver       start python server
    -php, --phpserver     start php server
    -ap2, --apache2       start apache2 server
    -ng, --nginx          start nginx server
    -v, --version         show version and exit
    
  stop service:
    -s, --stop            stop serving localhost service
  ```

<!--

<p align="center"><b>Open XAMP in Cloud Shell</b></p>
<p align="center">
  <a href="https://shell.cloud.google.com/cloudshell/open?cloudshell_git_repo=https://github.com/AdarshAddee/XAMP.git&tutorial=README.md" target="_blank"><img src="https://gstatic.com/cloudssh/images/open-btn.svg"></a>
</p>

-->

## Dependencies
These are the following dependencies which are used by XAMP!
- PHP
- Python
- Mariadb
- Apache2
- Nginx

All these dependencies are going to install automatically when you run <b>xamp</b> server for the first time.

## Mesaage
You can use xamp server without using ``./`` also. As this may help you to start services more faster.

## Sponsor
You can <b><a href="https://github.com/sponsors/AdarshAddee">sponsor</a></b> this repo also if you want.

<hr>

<b> XAMP उपयोग करने के लिए आपका धन्यवाद!<?b>







