# The Test Data for wsrf #

This reposiory holds the test data for
[wsrf](http://cran.r-project.org/web/packages/wsrf/index.html).

## Description ##

There are 9 datasets: *wap*, *la1s*, *la2s*, *re1*, *fbis*, *gisette*,
*newsgroups*, *tis*, and *mnist*.  All are seperated into two parts,
one for training (_*.data_), and the other for testing (_*.test_).
_*.names_ are associated variable (column) names for corresponding
datasets.

|Dataset    | Observations (Training)| Observations (Testing)|   Vars| Obs/Vars (Training)| Classes| Size (MB)|
|:----------|-----------------------:|----------------------:|------:|-------------------:|-------:|---------:|
|wap        |                   1,104|                    456|  8,460|                0.13|      20|      18.0|
|la1s       |                   1,963|                    887| 13,195|                0.15|       5|      50.0|
|la2s       |                   1,855|                    845| 12,432|                0.15|       5|      45.0|
|re1        |                   1,147|                    510|  3,758|                0.31|      25|       8.3|
|fbis       |                   1,711|                    752|  2,000|                0.86|      17|       6.6|
|gisette    |                   5,000|                    999|  5,000|                1.00|       2|      54.0|
|newsgroups |                  11,268|                  7,504|  5,000|                2.25|      20|     108.0|
|tis        |                   5,200|                  6,875|    927|                5.61|       2|       9.3|
|mnist      |                  48,000|                 10,000|    780|               61.54|       2|      84.0|

## Original Data ##

All the data are collected from the Internet:

* *fbis*, *la1s*, *la2s*, *re1*, and *wap* can be found at [Karypis
  Lab](http://glaros.dtc.umn.edu/gkhome/fetch/sw/cluto/datasets.tar.gz).

* *gisette* can be found at
  [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/machine-learning-databases/gisette/GISETTE/).

* *newsgroups* can be found at
  [20 Newsgroups by Jason Rennie](http://qwone.com/~jason/20Newsgroups/20news-bydate-matlab.tgz).

* *tis* can be found at
  [Guo-Zheng Li's Home Page](http://levis.tongji.edu.cn/gzli/data/TIS.zip).

* *mnist* can be found at
  [Data for MATLAB hackers by Sam Roweis](http://www.cs.nyu.edu/~roweis/data/mnist_all.mat).
