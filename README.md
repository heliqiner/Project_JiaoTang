# Project JiaoTang
*An ENVI Extension Aimed at Processing Imageries Taken by Chinese GaoFen Optical Satellites, Including GF1, GF2, GF4 and GF6*
# For Users
[Task file and already saved binary file](https://github.com/desertstsung/Project_JiaoTang/tree/master/userFile#about)
# For Interest
[Source code of this project](https://github.com/desertstsung/Project_JiaoTang/tree/master/sourceCode#all-pro-files)
# Releases
```V19.05.22```
+ optimization of NNDiffuse pan sharpening(when the pixel size of mss is not an integral multiple of the pixel size of pan, especially GaoFen6-PMS)

``V19.05.08``
+ code refactoring of subset by shapefile, using ENVI5 interface insead of Classic, removing mask operation for exchange
+ code simplify of unzip tgz file(s)

``V19.04.27``
+ new sensor GaoFen6-PMS/WFV supported
+ brand new batch mode
+ gzip file instead of image(s)
+ fix bug of subset via shapefile
+ adjust calibration coefficient of 2019
+ adjust registration after orthorectification
+ adjust adjunction of wavelength and units before calibration
+ adjust the method of dividing 10,000 on QUAC
+ adjust COMMON to DEFSYSV
+ remove tips prompt

``Before V19.04.27``
+ [My CSDN Blog](https://blog.csdn.net/desertsTsung/article/details/84679969)
