[Support UniversalBit Project](https://github.com/universalbit-dev/universalbit-dev/tree/main/support)

### OpenDNS Resolver and ping multiple hosts.

##### [Setup Nodejs](https://github.com/nvm-sh/nvm)
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
nvm i 20
```
```
git clone https://github.com/universalbit-dev/opendns-ping-multi.git
```
##### Install dependencies  * [PM2](https://pm2.io/docs/plus/quick-start/) * [Ping](https://www.npmjs.com/package/ping)
  
```
npm i && npm audit fix
```
##### Run opendns.js
```
pm2 start opendns.js
```
##### Log Views
```
pm2 logs
```

[Bash Reference Manual](https://www.gnu.org/software/bash/manual/html_node/index.html)
