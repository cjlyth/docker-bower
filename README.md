docker-bower
============

I use this in my .bashrc

```
alias bower='docker run --env="NPM_CONFIG_USER=1000" --env="NPM_CONFIG_GROUP=1000" -it --rm -v $PWD:/data cjlyth/bower bower '
```