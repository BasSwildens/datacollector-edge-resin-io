## StreamSets Data Collector Edge & Resin.io 

This is a simple skeleton [StreamSets Data Collector Edge][streamsets-data-collector-edge-link] project that works on any of the [resin.io][resin-link] supported devices.

This project deploys StreamSets Data Collector Edge agent on your resin.io device.

To deploy StreamSets Data Collector Edge on resin.io device, you will need to signup for a resin.io account [here][signup-page] and set up a device, have a look at our [Getting Started tutorial][gettingStarted-link]. 

Once you are set up with resin.io, you will need to clone this repo locally:
```
$ git clone git@github.com:madhukard/datacollector-edge-resin-io.git
```
Then add your resin.io application's remote repository to your local repository:
```
$ git remote add resin username@git.resin.io:username/myapp.git
```
and push the code to the newly added remote:
```
$ git push resin master
```
It should take a few minutes for the code to push.

Once the device is updated, you should see this in your logs:
![log output](/img/log-output.png)

Then in your browser you should be able to open the device URL (with port 18633) and see the StreamSets Data Collector Edge build information.

Then you can use StreamSets Data Collector UI to design/preview/start/stop Data Collector Edge pipelines on resin.io device.

![Data Collector UI](/img/datacollector-ui.png)


[streamsets-data-collector-edge-link]:https://streamsets.com/products/sdc-edge
[resin-link]:https://resin.io/
[signup-page]:https://dashboard.resin.io/signup
[gettingStarted-link]:http://docs.resin.io/#/pages/installing/gettingStarted.md
