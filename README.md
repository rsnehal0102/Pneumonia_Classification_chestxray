# Pneumonia-Detecter
## Abstract
Pneumonia is a life-threatening infectious disease affecting one or both lungs in humans commonly caused by bacteria called Streptococcus pneumoniae. One in three deaths in India is caused due to pneumonia as reported by World Health Organization (WHO). Chest X-Rays which are used to diagnose pneumonia need expert radiotherapists for evaluation. Thus, developing an automatic system for detecting pneumonia would be beneficial for treating the disease without any delay particularly in remote areas.
## Tools Used:
-Keras
-Numpy
-Pandas
-Seaborn and matplotlib
-Sklearn
-Cv2
## Data Augmentation
-Randomly rotate some training images by 45 degrees
-Randomly Zoom by 15% some training images
-Randomly shift images horizontally by 13% of the height
-Randomly shift images horizontally by 17% of the width
-Randomly flip some images horizontally.
### Note : These are also hyper-parameters which have been chosen randomly.
## Conclusion
I have demonstrated how to classify positive and negative pneumonia data from a collection of X-ray images. The model was made from scratch, which separates it from other methods that rely heavily on transfer learning approach. In the future this work could be extended to detect and classify X-ray images consisting of lung cancer and pneumonia. Distinguishing X-ray images that contain lung cancer and pneumonia has been a big issue in recent times, and our next approach should be to tackle this problem.
## Here are the images of the model
### Dataset
![1](https://user-images.githubusercontent.com/103516326/176655277-bfd5ecd4-5939-415b-9789-1f9d26064d54.jpg)
### Sample in Dataset
![2](https://user-images.githubusercontent.com/103516326/176655584-94172940-33cc-40a3-87d7-46bfa9d91e82.jpg)
### Loss and Accuracy v/s Epoches
![3](https://user-images.githubusercontent.com/103516326/176655748-88512d08-9098-44b7-88f7-eec931df5c0e.jpg)
### Correlation
![4](https://user-images.githubusercontent.com/103516326/176655825-3a19e46f-0a76-454d-8b33-84a92372ba0e.jpg)


