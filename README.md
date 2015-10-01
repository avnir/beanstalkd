# Beanstalkd docker container

This is a [Docker](http://www.docker.com) image for [Beanstalk](http://kr.github.io/beanstalkd/).

A few examples how to run these containers
- ```docker run -d --name beanstalkd avnir/beanstalkd```
- ```docker run -d --name beanstalkd -p 11300:11300 -p 60000:60000 avnir/beanstalkd```
- ```docker run -d -v ${PWD}:/data:rw --name beanstalkd avnir/beanstalkd```

Feedback or improvements are always welcome.