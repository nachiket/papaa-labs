Login to server with `PuTTY` or `ssh` then copy lab files to your user directory
```
$ cp -r /media/ubuntu-server/DataSt/HASS2017/Tutorial/day2/papaa-opencl/opencl-src ~/
$ cd ~/opencl-src/
```

There are 3 cpu labs in `cpu-labs` and 1 gpu lab in `gpu-labs`. Usage for each lab is the same:

From inside a lab directory, run OpenCL kernel using c host code:
```
$ make all
$ make run
```
Run OpenCL kernel using PyOpenCL:
```
$ make pyrun
```
