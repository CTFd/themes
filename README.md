# CTFd Theme Repository

This repository gathers open source CTFd themes from around the internet. Official premium themes can be found on the [CTFd Store](https://ctfd.io/store). 

Each theme provided here is stored as a gitsubmodule to the theme's project repository. 

# Installation
CTFd will automatically treat folders in the [CTFd/themes](https://github.com/CTFd/CTFd/tree/master/CTFd/themes) folder as themes to load. 

You can clone this repository and then copy or symlink the theme folders you wish to use to the [CTFd/themes](https://github.com/CTFd/CTFd/tree/master/CTFd/themes) folder. 

Because gitsubmodules are used, to clone this repository properly you should use the following command:

```bash
git clone --recursive https://github.com/CTFd/themes.git
```

It is possible to clone this repository directly into the CTFd/themes folder but that is left as a git exercise for the reader for the time being. 
