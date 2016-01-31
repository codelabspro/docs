Docs
----
The steps below are for running sails in production


Prerequisites

node : nvm use v5.5.0

Steps

npm install -g sails

sails new stacksdk

Running using forever

From

https://saintcoder.wordpress.com/2014/05/29/deploying-sails-js-web-application-on-aws-ec2-instance/

To run dev forever start -ae errors.log app.js --dev --port 1337

To run prod (first become root using sudo -s) forever start -ae errors.log app.js --prod --port 1337

To list forever processes forever list

To stop forever processes forever stop 0
