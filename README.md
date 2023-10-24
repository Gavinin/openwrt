# This Branch for OrangePi R1 Plus LTS

## How to install

```sh
git clone git@github.com:Gavinin/openwrt.git
cd openwrt

git checkout r1p-lts-23.05
git submodule init
git submodule update
./scripts/feeds update -a && ./scripts/feeds install -a
make menuconfig

```
