Define ZhuZhu Net
=======================
#### Check datafiles
* files need to record pairs of (datasource,label)

Data Layer
* [Data: Ins and Outs](http://caffe.berkeleyvision.org/tutorial/data.html)
  * ***Transformation***
     * Scale to [0-1] 
     * Crop
Convolution Layer
* [Explanation of Convolution Layer](http://caffe.berkeleyvision.org/tutorial/layers.html)
* Safely ingore ***'group'*** parameter when we handle the inputs with ***one channel***
  *  

Loss Layer
