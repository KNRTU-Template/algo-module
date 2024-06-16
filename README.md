# algo-module

### How to install GDAL
GDAL plays a crucial part in our approach so it's need to be installed.

https://gist.github.com/cspanring/5680334
```
apt install gdal-bin libgdal-dev
pip3 install GDAL==$(gdal-config --version) --global-option=build_ext --global-option="-I/usr/include/gdal"
```