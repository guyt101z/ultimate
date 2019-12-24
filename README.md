Insanely fast computer vision and deep learning frameworks. Almost entirely written in assembler, GPGPU accelerated, CPU optimized (SSE, AVX, ARM NEON) and massively multi-threaded, this is the fastest framework never released.

### Checkout the code ###

```
git clone --recurse-submodules https://github.com/DoubangoTelecom/ultimate.git
cd ultimate && chmod +x ./submodules-update.sh && ./submodules-update.sh
cd ultimateCloud && mkdir build && cd build
cmake ..
make
```

### SDKs using our code ###

 - <a target="_blank" href="https://github.com/DoubangoTelecom/ultimateALPR-SDK">ANPR/ALPR SDK for embedded devices (ARM) and desktops (x86) </a>
  - <a target="_blank" href="https://github.com/DoubangoTelecom/ultimateMRZ-SDK">MRZ/MRP SDK for embedded devices (ARM) and desktops (x86) </a>
 
 ### Online demo apps using our code ###
 - <a target="_blank" href="https://doubango.org/webapps/alpr/">Cloud-based Automatic Number/License Plate Recognition (ANPR/ALPR)</a>
 - <a target="_blank" href="https://doubango.org/webapps/mrz/">Cloud-based Machine-readable zone/passport (MRZ/MRP)</a>
 - <a target="_blank" href="https://doubango.org/webapps/micr/">Cloud-based Magnetic ink character recognition (MICR E-13B & CMC-7)</a>
 - <a target="_blank" href="https://doubango.org/webapps/cbir/">Cloud-based Content-Based Image Retrieval (CBIR)</a>
 - <a target="_blank" href="https://doubango.org/webapps/ocr/">Cloud-based Scene text recognition (TextInWild)</a>
 
 ### Technical questions ###
 Please check our [discussion group](https://groups.google.com/forum/#!forum/doubango-ai) or [twitter account](https://twitter.com/doubangotelecom?lang=en)
