# TensorFlow_ObjectDetectionAPI_Hand_Detection
Training a TensorFlow Object Detection Classifier to Detect and Track Hands in Real Time

## Requirements:
- Anaconda Package Manager
- Cuda & cuDNN (Optional)
- Python 3.5
- Latest version of TensorFlow (TensorFlow-GPU if you have a GPU that can handle the job, check nVIDIA/CUDA's website to learn.)

For the sake of speed, I have used ssdmobilenet, as I will be detecting hands in Real-Time. But feel free to try other pre-trained models as well.

EgoHands Datasets was used in this project to train the model. (link to their website below) I haven't tried Oxford's Hand Dataset yet, you might want to give it a try if you don't get the desired performance with EgoHands.

I won't be providing a full walkthrough in this repo, as EdjeElectronics have already done so. If you want to train your model from zero to hero, you can check their repo. (Link in References)

References:

- [Sentdex's Tutorial on Object Detection API](https://pythonprogramming.net/introduction-use-tensorflow-object-detection-api-tutorial/)
- [Victor Dibia's hand detection](https://github.com/victordibia/handtracking)
- [Datitran's Raccoon Dataset](https://github.com/datitran/raccoon_dataset)
- [Edje Electronics' ObjDet API Tutorial](https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10)
- [Ego Hands Dataset](http://vision.soic.indiana.edu/projects/egohands/)
- and obviously, [Tensorflow model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)
