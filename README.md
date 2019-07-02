# TensorFlow_ObjectDetectionAPI_Hand_Detection
Training a TensorFlow Object Detection Classifier to Detect and Track Hands in Real Time

## Requirements:
- Anaconda Package Manager
- Cuda & cuDNN (Optional)
- Python 3.5
- Latest version of TensorFlow (TensorFlow-GPU if you have a GPU that can handle the job, check nVIDIA/CUDA's website to learn.)
- Latest version of protobuf

For the sake of speed, I have used ssdmobilenet, as I will be detecting hands in Real-Time. But feel free to try other pre-trained models as well.

EgoHands Datasets was used in this project to train the model. (link to their website below) I haven't tried Oxford's Hand Dataset yet, you might want to give it a try if you don't get the desired performance with EgoHands.

You can also train the models for any other object/s you wish to work with. All you have to do is create the tfrecords(generate_tfrecords.py) for the dataset you will be using, configure your .config and labelmap files according to your labels and the number of objects you will be working with. **Make sure you set the file paths right in the .config file of the model you will be using.**

I won't be providing a full walkthrough in this repo, as EdjeElectronics have already done so. If you want to train your model from zero to hero, you can check [their repo](https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10).

## Possible Errors:

**Make sure you copy the repo into "C:/tensorflow1". I've had path errors before doing so, you are free to try otherwise but if you get errors, this may be your solution.**

**As mentioned in [EdjeElectronics' repo](https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10), Tensorflow often update their repos and you may get error like "ImportError: cannot import blah blah". Then you should go on and check your protos file to see if you have any missing .py pairs of the .proto files.**

References:

- [Sentdex's Tutorial on Object Detection API](https://pythonprogramming.net/introduction-use-tensorflow-object-detection-api-tutorial/)
- [Victor Dibia's hand detection](https://github.com/victordibia/handtracking)
- [Datitran's Raccoon Dataset](https://github.com/datitran/raccoon_dataset)
- [Edje Electronics' ObjDet API Tutorial](https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10)
- [Ego Hands Dataset](http://vision.soic.indiana.edu/projects/egohands/)
- and obviously, [Tensorflow model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)
