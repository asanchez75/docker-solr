# SOLR docker container for Drupal

This docker container is designed to be used with the SOLR configuration files of the [ApacheSolr module](https://www.drupal.org/project/apachesolr)

For this example, such a  module has been cloned and added to the git repository by using this command

```
git submodule add -b 7.x-1.x https://git.drupal.org/project/apachesolr.git  apachesolr
```

The docker image comes from https://hub.docker.com/_/solr/

The SOLR url will be available here 

http://localhost:8983/solr/#/~cores/mycore

and the SOLR server URL to be added into the Drupal UI is

http://solr:8983/solr/mycore

 



