# LogicalVision2 [Under Construction] #

Symbolic computer vision tool with SWI-Prolog and OpenCV.

## Requirement ##

1. SWI-Prolog (>=7.0) compiled with `EXTRA_PKGS=clib`.

2. OpenCV (>=3.0).

3. Armadillo library for matrix handling.

4. [Optional] Qt5 if you want a moderner OpenCV displaying, complile your OpenCV with Qt option on.

## Compile ##

`cd src/ && make`

## Usage ##

After compilation you will get `cvio.so`, `cvdraw.so` and `cvsampler.so` in `src/prolog2` folder. Simply load them in SWI-Prolog with:

> `load_foreign_library(foreign('src/prolog2/cvio.so')).`

> `load_foreign_library(foreign('src/prolog2/cvsampler.so')).`

> `load_foreign_library(foreign('src/prolog2/cvdraw.so')).`

Please see the source codes for detail predicates.

## Contact ##

Wang-Zhou Dai

LAMDA Group, Nanjing University

[daiwz@lamda.nju.edu.cn](mailto:daiwz@lamda.nju.edu.cn)

[http://lamda.nju.edu.cn/daiwz](http://lamda.nju.edu.cn/daiwz)

