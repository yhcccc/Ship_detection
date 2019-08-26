# Mask R-CNN for Airbus Ship Detection Challenge  

#### Reference :  
[matterport/Mask_RCNN](https://github.com/matterport/Mask_RCNN)  
[Fine-tuning ResNet34 on ship detection](https://www.kaggle.com/iafoss/fine-tuning-resnet34-on-ship-detection-new-data)  
  
#### Requirements:   
Python 3.6, TensorFlow 1.3, Keras 2.0.8 and several common packages.   
  
#### Main concern:   
Rotation invariance                         -- Data Augmentation;  
Samples with ~1:10000 unbalance(pos:neg)    -- Combine with ResNet34 classification results;  
Not duplicated in the decoded pixel values  -- ```(mask^bg)&mask```(in ship_detection.ipynb);

Run ship_detection.ipynb.
