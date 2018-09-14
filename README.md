# edi-debian

edi is mainly being developed using Ubuntu 18.04 LTS.
To do some random testing on Debian I use this edi configuration to setup a Debian container.

Example:

``` bash
sudo edi -v lxc configure debian-stretch stretch.yml
```

Within the container edi can be setup according to the [getting started guide](https://docs.get-edi.io/en/latest/getting_started.html).

The following tests verify the basic functionality:

``` bash
py.test-3
sudo py.test-3 --all
```
