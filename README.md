# Amazon EC2 Container Service Plugin for Jenkins

[![Build Status](https://jenkins.ci.cloudbees.com/job/plugins/job/amazon-ecs-plugin/badge/icon)](https://jenkins.ci.cloudbees.com/job/plugins/job/amazon-ecs-plugin/)

## About

This jenkins plugin do use [Amazon EC2 Container Service](http://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html) to host jobs execution inside docker containers.

* see [Jenkins wiki](https://wiki.jenkins-ci.org/display/JENKINS/Git+Plugin) for detailed feature descriptions
* use [JIRA](https://issues.jenkins-ci.org/issues/?jql=project %3D JENKINS AND status in (Open%2C "In Progress"%2C Reopened) AND component %3D amazon-ecs-plugin) to report issues / feature requests


## Building the Plugin

```bash
  $ java -version # Need Java 1.8, earlier versions are unsupported for build
  $ mvn -version # Need a modern maven version; maven 3.2.5 and 3.5.0 are known to work
  $ mvn clean install
```

To run locally, execute the following command and open the browser [http://localhost:8080/jenkins/](http://localhost:8080/jenkins/)

```bash
  $ mvn -e hpi:run
```


## Documentation and Installation

Please find the documentation on the [Jenkins Wiki page Amazon EC2 Container Service Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Amazon+EC2+Container+Service+Plugin).
