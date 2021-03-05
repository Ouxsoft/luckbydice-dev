<p align="center"><img src="https://raw.githubusercontent.com/ouxsoft/LuckByDice/main/docs/logo.png" width="400"></p>

# LuckByDiceDev

A stack environment dedicated to continuously deploying the [LuckByDice](https://github.com/ouxsoft/LuckByDice) 
package.

## Getting Started

Clone repo using [Git](https://git-scm.com/downloads).
```shell script
git clone --recurse-submodules git@github.com:ouxsoft/luckbydice-dev.git
```
Run `git submodule update --init` to add submodule after git clone.

Start the stack environment using the shell script and [Docker](https://www.docker.com/products/docker-desktop).
```shell script
./stack start
```

After making code changes to `./app` sub module repository use pipeline to test and deploy.

| Service | URL | Username | Password |
| --- | --- | --- | --- |
| CI/CD Pipeline | http://cd.localhost/blue/ | admin | admin |


### Need help?
```shell script
./stack help
```
