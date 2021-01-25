# jenkins kubernetes helm deployment with custom jenkins configuration

One click Jenkins deployment in kubernetes cluster using helm with custom jenkins default configurations and superseed job to create jenkins pipeline automatically.

# Features!:
  - One click deployment
  - Preinstalled cloud and required plugins
  - Preconfigured Superseed job to create jenkins pipeline
  - Default jenkins system configuration for cloud based deployment like Aritifactory URL, Gerrit   URL, email configuration,

# Requirements:
  - Ubuntu 20 with 5Gb ram and 50Gb storage and 1 CPU (Min.).
  - Helm 3
  - Kubernetes cluster.
  - Make
  - Git
  
### Installation

```
$ sudo su
$ git clone <repo>
$ cd jenkins-kubernetes-helm-deployment
 Note: you can update CPU, RAM, Volume, and Other configuration in values.yaml file
$ ./deploy_jenkins_chart.sh
```

Jenkins UI can be access via node port IP or Ingress IP.
