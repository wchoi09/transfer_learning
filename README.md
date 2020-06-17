# transfer_learning
Using transfer learning (fine tuning) with Tensorflow 2 and Keras to compare different CNN architectures


What is Transfer Learning?  
Transfer learning is a method of using pre-trained model which is a saved network that was previously trained on a large dataset.  
There are two types of transfer learning:  
1. Feature Extraction  
2. Fine Tuning  

I will be fine tuning the models on food-11 dataset.  

The directory structure is important.  
This is how the project tree will look like:  
```bash
transfer_learning
|-- dataset               
|   |-- evaluation                  # containes 11 sub-directories of classes
|   |-- training                    # containes 11 sub-directories of classes
|   `-- validation                  # containes 11 sub-directories of classes
|-- model                           # directory for saving model.h5 after training has completed
|-- output                          # directory for saving plot.png after training has completed
`-- fine_tuning_train_custom.py     # main python script for training (fine tuning)
```


Requirements:  
TBA  
Works on Tensorflow 2.2!  

Resources  
Transfer learning & fine-tuning [https://keras.io/guides/transfer_learning/]  
Transfer learning with a pretrained ConvNet [https://www.tensorflow.org/tutorials/images/transfer_learning]  
