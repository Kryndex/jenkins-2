# jenkins
> Configuration for IPFS's build system

## WIP: In the process of being setup

You can follow along with the issues listed over at https://github.com/ipfs/jenkins/issues

## Development Environment Setup

### Requirements

* Docker

### Intructions

* Clone repository
* Run `./start-dev.sh`
* Now jenkins should be running at http://localhost:8080

```
username: admin
password: admin
```


## Notes

Secrets are only valid for dev-environment. Make sure to only run jenkins in dev
listening to 127.0.0.1 and not 0.0.0.0. Secrets are replaced when jenkins is deployed
