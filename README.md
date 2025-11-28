# WT-Gadi.AU

Compiling WannierTools 2.7.0 on Gadi, NCI, AU

These modules need to be loaded
```shell
module load intel-compiler/2021.1.0
module load intel-mkl/2022.2.0
module load openmpi/4.1.7

```

ARPACK is supported through adding this in Makefile (already added)
```shell
# ARPACK LIBRARY
ARPACK=/apps/arpack-ng/3.7.0/lib/Intel/libarpack.a
```

Only Makefile is provided in this repository (rename it to Makefile and place it under /src), to download the 2.7.0 release, use:
```shell
wget https://github.com/quanshengwu/wannier_tools/archive/refs/tags/v2.7.0.zip
```

