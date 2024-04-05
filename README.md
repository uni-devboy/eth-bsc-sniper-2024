# description
auto buy any eth chain such as BSC/ETH etc with fast sniper. Using multi threading to speed up the tx.
buy multiple times or in one go
Antibot function checks
Owner blacklist functions

## Installation
Download the repo with

```bash
git clone https://github.com/uni-devboy/eth-bsc-sniper-2024
cd eth-bsc-sniper-2024
```
Then edit env.json and save your changes

```json
{
    "PRIVATE_KEY": "REPLACEME with your private key",
    "YOUR_ADDRESS": "REPLACEME with your address that will buy",
    "NODE": "https://bsc-dataseed.binance.org/",  //replace with another node or leave this one here 
    "TOKEN": "CONTRACTTOSNIPEADDRESSHERE", //replace with the contract address you wish to snipe 
    "presale": "true", //if the snipe is presale or not
    "INVESTMENT": "BNB OR ETHER VALUE HERE", //replace with the number with decimals such as 0.01 or 5.1 etc. The currency ETHER or BNB is determined by which node, if you use a BSC node you will be paying in BNB here
    "GASLIMIT": "1000000", //custom gas limit
    "GWEI": "5",
    "AUTOSELL": "TRUE",  //if true then the bot will detect profits and sell for you
    "AUTOSELLPERCENT": "110",  //set the % profit to sell at
    "STOPLOSSPERCENT": "5", //Pecentage stop loss
    "SELLTOKENSIN-STAGES-X": "TRUE", //If you want only a portion to sell when auto sell percentage is hit, IF ITS YES THEN IT SELLS 3 TIMES, First time is based on Autosell percent
    "SELLSTAGES-X2": "300",  //Second sell is based on this % increase
    "SELLSTAGES-X3": "500",  //Third sell is based on this % increase
    "HONEYPOTCHECK": "TRUE", //if honeypot detection is on or off
    "MINLIQ": "1", //contract must have this amount of liq at minimum such as 1 eth or 1 bnb
    "MAXLIQ": "150" //contract must have this amount of liq at maximum such as 100 eth or 100 bnb
}
REMOVE COMMENTS SO IT LOOKS LIKE THIS BELOW:
{
    "PRIVATE_KEY": "REPLACEME",
    "YOUR_ADDRESS": "REPLACEME",
    "NODE": "PUT YOUR NODE HERE",
    "TOKEN": "CONTRACTTOSNIPEADDRESSHERE",
    "PRESALE": "false",
    "INVESTMENT": "BNB OR ETHER VALUE HERE",
    "GASLIMIT": "1000000",
    "GWEI": "5",
    "AUTOSELL": "TRUE",
    "AUTOSELLPERCENT": "110",
    "STOPLOSSPERCENT": "5",
    "SELLTOKENSIN-STAGES-X": "TRUE",
    "SELLSTAGES-X1": "2",
    "SELLSTAGES-X2": "3",
    "SELLSTAGES-X3": "10",
    "HONEYPOTCHECK": "TRUE",
    "MINLIQ": "1",
    "MAXLIQ": "100"
}
``` 

Run Powershell or a terminal

```json
  npm i
  node app.js
```


<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://backbonejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/backbonejs/backbonejs-original-wordmark.svg" alt="backbonejs" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://clojure.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/5/5d/Clojure_logo.svg" alt="clojure" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://lucene.apache.org/solr/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_solr/apache_solr-icon.svg" alt="solr" width="40" height="40"/> </a> <a href="https://vuejs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" alt="vuejs" width="40" height="40"/> </a> </p>

Tags: 
binance smart chain sniper bot
Mempool sniper
Pcs sniper
Pancakeswap
Ethereum sniper
Dxsale sniper
Snipe bot
2023 sniper
ethereum snipe
sniper bot
uniswap sniper
dxsale snipe
