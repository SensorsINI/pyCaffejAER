# pyCaffejAER
A collection of utilities useful to debug deep-networks trained with Caffe Deep Learning Framework. 
This utilities can also be used to convert caffe networks into jAER xml format


# cnn to xml (caffe to jAER conversion)
<br />
$ cnn_to_xml.py<br />
<br />
Converts caffe networks into jAER xml format <br />
 this script requires command line arguments:  <br />
                         model file -> network.prototxt   <br />
                         weights file -> caffenet.model<br />
                        OR<br />
                         if you pass a directory it will look for these files<br />
Example usage:<br />
     python python/cnn_to_xml.py caffe_network_directory/ (it looks for .caffemodel and .prototxt)<br />
