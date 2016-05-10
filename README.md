# `CNVnator` packages

This repository contains binary debian packages of [`CNVnator`][1] based on using [cnvnator-packager][2].  They are intended for various [Ubuntu Linux distributions][3].

## Quick Download Links & Install Instructions

All the debian packages are targeted for amd64 architecture machines.

### Ubuntu 10.04

#### Download Links

* [Ubuntu 10.04 (lucid) gcc-4.8.4][4]
* [Ubuntu 10.04 (lucid) cnvnator-0.3.2][5]

#### Installation Process

```
sudo apt-get install libc6 zlib1g libgomp1 liblzma1 libpcre3 libfreetype6 libmpc2
sudo dpkg -i gcc_4.8.4-1ubuntu10.04.deb
sudo dpkg -i cnvnator_0.3.2-1ubuntu10.04.deb
```

### Ubuntu 14.04

#### Download Links

* [Ubuntu 14.04 (trusty) cnvnator-0.3.2][6]

#### Installation Process

```
sudo apt-get install build-essential libc6 zlib1g libgomp1 libstdc++6 libgcc1
sudo dpkg -i cnvnator_0.3.2-1ubuntu14.04.deb
```


[1]: https://github.com/abyzovlab/CNVnator
[2]: https://github.com/indraniel/cnvnator-packager
[3]: http://www.ubuntu.com
[4]: https://github.com/indraniel/cnvnator-packages/releases/download/v0.3.2-1/gcc_4.8.4-1ubuntu10.04.deb
[5]: https://github.com/indraniel/cnvnator-packages/releases/download/v0.3.2-1/cnvnator_0.3.2-1ubuntu10.04.deb
[6]: https://github.com/indraniel/cnvnator-packages/releases/download/v0.3.2-1/cnvnator_0.3.2-1ubuntu14.04.deb
