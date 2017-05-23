The focus of this guide is mainly related to Addon aka Binding development for OpenHab, however it might contain useful information for openhab development in general.
This guide is by intent a very low level collection of coding stuff, its raw, dirty, quick but essential, it might outdate fast, please keep an eye to the forum and official OpenHab documentation. Changes and contributions are highly appreciated.
 
# Git and GitHub

   Some love it, some hate it, all must use it. To contribute to OpenHab some fundamental terms are important to know, before starting coding you should know at least following terms and know how to manage them: fork, pull request, upstream, branch, merge

# OpenHab Developer Guide

   Fundamental developer information:
   http://docs.openhab.org/developers/contributing/contributing

## IDE environment
   
   Initial setup: http://docs.openhab.org/developers/development/ide.html
   
   Update of environment: Eclipse->Help->Perform Setup Tasks
   
   ### Run configurations
   
   Run configurations can be configured in Eclipse to chose which addons are activated in your development: Eclipse->Run->Run configurations->Plug-ins  


## Create pull requests

   OpenHab and its modules are organized in Github, see fundamental information above. To start a development fork, after this commit and pull, when everything is tested a pull request might be  initiated to upstream.

## Create pre release jar

   The pull requests to upstream master of OpenHab are usually checked in a Jenkins build. This also makes it possible to have a pre release jar for testing purpose under following address: https://openhab.jfrog.io/openhab/libs-pullrequest-local/org/openhab/binding/xBINDINGx/xRELEASEx/xBINDING_JARx.jar  

## Signoff code

   Every code commit has to be signed off, please read the details here:
   http://docs.openhab.org/developers/contributing/contributing

## Build checks

When pull requests are issued, Jenkins build is performing code analyses.
How this can be done in Eclipse?


## Clean environment

Mainly after upgrades and version changes it migth be necessary to clean all personal settings and environment. Otherwise nasty side effects in the UI are likely.
So it is recommend to backup and remove following directory: *BASE_DIRECTORY*/openhab2/git/openhab-distro/launch/home/userdata <sup>[1]</sup>  

## How to manage code and library dependencies

   :TODO:
   
## About file

   :TODO:
   
## Skeletons
   
   :TODO:
   
   

[1]: https://community.openhab.org/t/recommended-way-to-backup-restore-oh2-configurations-and-things/7193/10