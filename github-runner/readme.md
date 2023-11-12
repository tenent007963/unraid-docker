# Github-Runner
A self-hosted GitHub action runner in Docker image.   
Because most of the existing one doesn't work properly, so here I am (here we are)

## Requirements
Docker installed. or UNRaid docker properly set up

## Parameters
Name/Key | Value 
--- | --- 
URL | URL from GitHub* 
TOKEN | Token for runner

*\*as of version v2.311.0, both organization link and repository link are acceptable and tested to be fine.*

## Improvements
Is it possible to create multiple nested docker containers to host multiple runners at once?

## Special Thanks
Thanks to [binhex](https://github.com/binhex/docker-templates/) for providing CA template.
