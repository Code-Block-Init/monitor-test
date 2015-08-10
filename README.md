# monitor-test
***
<b><i>Monitoring and Analytics App in IBM BlueMix for <a href="https://github.com/node-red">node-red</a> using CloudFoundry in Windows</b></i>
***
***
<b>Requirements:</b> <br>
--- <a href="https://github.com/cloudfoundry/cli/">CloudFoundry-CLI</a><br>
--- <a href="http://nodered.org/">Node-Red</a>
***
```sh
dell@DELL3521 ~
$ cd /d/bluemix/node-mix

dell@DELL3521 /d/bluemix/node-mix
$ cf api https://api.eu-gb.bluemix.net

dell@DELL3521 /d/bluemix/node-mix
$ cf login -u ashumeow@live.com

dell@DELL3521 /d/bluemix/node-mix
$ cf target -o ashumeow_org -s dev

dell@DELL3521 /d/bluemix/node-mix
$ cf push monitor-test
```
