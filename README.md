# Target Server for DDoS Attack
This is sketch web server implemented with nodejs.

The web site will refresh every 3sec and render pages with random images from internet.

So, you can easily tell if the DDoS attack is really affecting the server.


## Requirements
- OS: Linux 16.04
- Node, npm
- firewall should be disabled [**see detail**](https://www.carnaghan.com/knowledge-base/how-to-enable-and-disable-the-firewall-on-ubuntu-16-04/)
- SYN Cookie should be disabled [**see detail**](https://geode.apache.org/docs/guide/19/managing/monitor_tune/disabling_tcp_syn_cookies.html)


## installation
### 1. install node
``` $ sudo apt-get install nodejs ```

this command will install node with npm if npm is not installed, you should install manually checkout this [link](https://www.npmjs.com)

##### Check Node.js and NPM are installed
``` $ node -v && npm -v ```

### 2. Install npm modules 

You should install modules so that node can launch server

You can install modules with command below in root directory

``` $ npm install ```

### 3. Run server
``` $ npm start ```


checkout http://localhost:3000 and you can see pages below


![alt text](img/img1.png)
