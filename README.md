# demo-building-a-javascript-development-environment
Building a JavaScript Development Environment

1. To check package security, we need to install node security platform
npm install -g nsp
nsp check

2. How to sharing work-in progress
   install localtunnel: npm install -g localtunnel
   run app: node buildScripts/srcServer.js
   share: lt --port 3000 --subdomain phuongtt
   
3. Continuous Integration
  * Register account on travis-ci.org and do follow document
  * Register account on appveyor.com and do follow document
