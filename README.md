cf-wordpress
============

CloudFoundry sample Wordpress install


### Configuring the CloudFoundry CLI
```
gem install cf
cf target api.run.pivotal.io
cf login [your-cloudfoundry-email]
```

### Pushing the sample app
```
git clone https://github.com/danielgrippi/cf-wordpress.git
cd cf-wordpress
cf push
```
