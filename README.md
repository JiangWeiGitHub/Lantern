# Building Lantern for running on a server

+ **Reference Link**<p>
  - [**Offical Doc**](https://github.com/getlantern/lantern)

+ **Prerequisite**<p>
  - **Operating System:** *Ubuntu 16.04 server x64*<p>
  - *Git* - `apt-get install git`<p>
  - [*Go 1.6 or higher*](https://golang.org/dl/) - `wget https://storage.googleapis.com/golang/go1.6.2.linux-amd64.tar.gz`<p>
  - *GNU Make*<p>
  - *Nodejs & NPM* - `wget https://nodejs.org/dist/v6.2.0/node-v6.2.0-linux-x64.tar.xz`<p>
  - *GNU C Library* - `apt-get install libc6-dev-i386 build-essential`<p>
  - *Gulp* - `npm i gulp-cli -g`<p>
  
+ **Procedure**
```
  git clone https://github.com/getlantern/lantern.git
  cd lantern
  HEADLESS=true make linux
  ./lantern_linux_amd64 --addr 0.0.0.0:8787
```

+ **Usage**
<center>
![Proxy](https://github.com/JiangWeiGitHub/Lantern/blob/master/lantern.jpg)
</center>
