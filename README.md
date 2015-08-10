# monitor-test
***
Monitoring and Analytics App in IBM BlueMix for <a href="https://github.com/node-red">node-red</a> using CloudFoundry in Windows
***
***
Requirements: <br>
<a href="https://github.com/cloudfoundry/cli/">CloudFoundry-CLI</a>
***
```sh
dell@DELL3521 ~
$ cd /d/bluemix/CloudFoundry

dell@DELL3521 /d/bluemix/CloudFoundry
$ cf api https://api.eu-gb.bluemix.net

dell@DELL3521 /d/bluemix/CloudFoundry
$ cf login -u ashumeow@live.com

dell@DELL3521 /d/bluemix/CloudFoundry
$ cf target -o ashumeow_org -s dev

dell@DELL3521 /d/bluemix/CloudFoundry
$ cf push monitor-test
```
