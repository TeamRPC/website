# website
the teamrpc website


## notes

This project is dockerized. to run, use:

    docker run -it --rm --name teamrpc teamrpc-website



## updating submodules

to update submodules, run:

```
git submodule foreach git pull origin master
```

then add and commit submodule directories