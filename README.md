## StreamSets Data Collector Edge & Resio.io 

This is a simple skeleton [StreamSets Data Collector Edge][steamsets-data-collector-edge-link] project that works on any of the [resin.io][resin-link] supported devices.

This project starts StreamSets Data Collector Edge agent on your resin.io device.

To get this project up and running, you will need to signup for a resin.io account [here][signup-page] and set up a device, have a look at our [Getting Started tutorial][gettingStarted-link]. 

Once you are set up with resin.io, you will need to clone this repo locally:
```
$ git clone git@github.com:resin-projects/simple-server-node.git
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


[streamsets-data-collector-edge-link]:https://streamsets.com/products/sdc-edge
[resin-link]:https://resin.io/
[signup-page]:https://dashboard.resin.io/signup
[gettingStarted-link]:http://docs.resin.io/#/pages/installing/gettingStarted.md
