infinispan-openshift-distributed-cache-example
==============================================

A sample OpenShift application using Infinispan as distributed cache.

Create a scalable application

```
rhc app create demoapp jbossas-7 -s
```

Pull the soure from github

```
git remote add upstream https://github.com/shekhargulati/infinispan-openshift-distributed-cache-example.git
git pull -s recursive -X theirs upstream master
```

Push the source code

```
git push
```

The application will be avalable at http://demoapp-{domain-name}.rhcloud.com. Replace {domain-name} with your own domain name.
