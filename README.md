# renovate-config
Created per https://renovatebot.com/docs/config-presets and published to our private NPM repo. This will allow Pager to have 1 common config that can be in various projects. The main benefit is to have only 1 place to update packages. Config can still be overriden in each individual project, for flexibility.

## How to use
In `package.json` of a project, add the following section:
```
  "renovate": {
    "extends": ["@pager:api-stable"]
  }
```

Ensure that this package (renovate-config) is published to the Pager private npm repo.

## api-stable package rules
Package names: `hapi`  
Versions allowed: <17  
Reason: breaking changes from 16 -> 17  

Package names: `hoek`, `rejoice`, `scooter`  
Versions allowed: <5  
Reason: 

Package names: `h2o2`  
Versions allowed: <7  
Reason: h2o2 v7 and beyond require Hapi 17  

Package names: `good`  
Version allowed: <8  
Reason:   

Package names: `lab`  
Version allowed: <15  
Reason:  

Package names: `mongoose`  
Vesion allowed: <5  
Reason:  

## api-dev package rules
