# pyCaffejAER
A collection of utilities useful to debug deep-networks trained with Caffe Deep Learning Framework. 
This utilities can also be used to convert caffe networks into jAER xml format


# cnn to xml (caffe to jAER conversion)

cnn_to_xml.py

Converts caffe networks into jAER xml format
 this script requires command line arguments: 
                         model file -> network.prototxt  
                         weights file -> caffenet.model
                        OR
                         if you pass a directory it will look for these files
Example usage:
     python python/cnn_to_xml.py caffe_network_directory/ (it looks for .caffemodel and .prototxt)
