# renovate-config
Created this per https://renovatebot.com/docs/config-presets and published to our private NPM repo. This will allow Pager to refer to this config in other projects and have it apply to those projects. The main benefit is to have only 1 place to update. Config can still be overriden in each individual project, for flexibility.

## Base config restrictions
Package names: `hapi`  
Versions allowed: <17  
Reason: breaking changes from 16 -> 17  

Package names: `hoek`, `rejoice`, `scooter`  
Versions allowed: <5  
Reason:  

Package names: `good`  
Version allowed: <8  

Package names: `lab`  
Version allowed: <15  

Package names: `mongoose`  
Vesion allowed: <5  