# Target Server for DDoS Attack
This is sketch web server implemented with nodejs.

This web site will refresh every 3sec so that you can easily tell if the DDoS attack is affect the server




## Requirements
- OS: Linux 16.04
- Node, npm
- firewall should be disabled
- SYN Cookie should be disabled


## installation
### 1. install node
``` $ sudo apt-get install nodejs ```

this command will install node with npm if npm is not installed, you should install manually checkout this [link](https://www.npmjs.com)

##### Check Node.js and NPM is installed
``` $ node -v ```

``` $ npm -v ```

### 2. Install npm modules 

You should install modules so that node can launch server

You can install modules with command below in root directory

``` $ npm install ```

### 3. Run server
``` $ npm start ```


checkout http://localhost:3000



![alt text](img/img1.png)
