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
![Dataset](https://user-images.githubusercontent.com/54640931/124766717-c927ae80-df54-11eb-8e0a-d24cb305fe50.png)
### Sample in Dataset
![Sample in DataSet](https://user-images.githubusercontent.com/54640931/124766765-d47ada00-df54-11eb-9917-ba5a87f29f9c.png)
### Loss and Accuracy v/s Epoches
![Loss](https://user-images.githubusercontent.com/54640931/124766814-e197c900-df54-11eb-8e00-be9fad9cb8d2.png)
### Correlation
![Correlation](https://user-images.githubusercontent.com/54640931/124766863-ebb9c780-df54-11eb-9921-5548598d3b17.png)


