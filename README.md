cf-wordpress
============

CloudFoundry sample Wordpress install


### Configuring the CloudFoundry CLI
```
gem install cf
cf login [your-cloudfoundry-email]
cf target api.run.pivotal.io
cf space development
```

### Pushing the sample app
```
git clone https://github.com/danielgrippi/cf-wordpress.git
cd cf-wordpress
cf push
```
