# CV-Assignment-3 (Multi-class classification using CNN)
Implementation of an image classification pipeline using CNN to classify the natural scenes images into different classes. 

VGGnet CNN architecture is used in Keras. The different training settings, network diagrams, confusion matrics, graphs of training and validation losses and accuracies are shown in each code.

# How to run the codes?
1. Upload each Python file in a separate Colab file.
2. Upload the test data separately. (I made a small folder of the larger set)
3. Run all to get the results.



# Methodolgies and results


[1.] VGGnet is built from scratch and is trained on Intel image classification dataset. Using different parameters to get best 
training accuracy of 96.20%

validation accuracy of 80.59%

test accuracy of 78.67%

The training and validation accuracy plot of this part is:


![self_made_best_plot](https://user-images.githubusercontent.com/36454438/103892646-bb13e500-510d-11eb-95ca-40888637bcac.png)

The training and validation accuracy plot showing all experimentations is:



![self made all](https://user-images.githubusercontent.com/36454438/103893013-586f1900-510e-11eb-8225-4771144df14b.png)




[2.] VGGnet is built from scratch and is trained on augmented Intel image classification dataset. Using different parameters to get best 
training accuracy of 97.03% 


validation accuracy of 80.63%

test accuracy of 79.23%

The training and validation accuracy plot of this part is:


![self made best plot image aug](https://user-images.githubusercontent.com/36454438/103893305-f367f300-510e-11eb-9df0-ab8fa6c3fe88.png)


The training and validation accuracy plot showing all experimentations is:



![self made image aug all](https://user-images.githubusercontent.com/36454438/103893322-fa8f0100-510e-11eb-8722-4f21cf26c435.png)




[3.] Pre-implemented VGGnet is used on Intel image classification dataset with Transfer learning technique. Using different parameters to get best  

training accuracy of 70.55% 


validation accuracy of 69.80%

test accuracy of 72.33%

The training and validation accuracy plot showing best results is:


![transfer learning best plot](https://user-images.githubusercontent.com/36454438/103896720-38daef00-5114-11eb-95d9-609354c9f117.png)


The training and validation accuracy plot showing all experimentations is:


![transfer learning all plots](https://user-images.githubusercontent.com/36454438/103896884-7dff2100-5114-11eb-84db-cee365f91982.png)



[4.] Pre-implemented VGGnet is used on augmented Intel image classification dataset with Transfer learning technique. Using different parameters to get best

training accuracy of 76.90% 


validation accuracy of 74.23%

test accuracy of 72.48%

The training and validation accuracy plot using augmentation and showing best results is:


![SGD l,a plot crop](https://user-images.githubusercontent.com/36454438/103899346-18149880-5118-11eb-907c-786c6a474d33.png)


The training and validation accuracy plot showing all experimentations is:

![all l,a crop aug](https://user-images.githubusercontent.com/36454438/103899396-2793e180-5118-11eb-8d4d-7cd5135bdb15.png)



The result of trained model is visualized in following figure which shows that the test labels have been correctly predicted and hence our model is accurately classifying images of dataset.


![inference](https://user-images.githubusercontent.com/36454438/103930676-f085f600-5140-11eb-904d-db1060eb6682.png)




[1.]: https://github.com/AmeeraArif09/CV-Assignment-3/blob/main/Codes/cvA3(selfmade_with_origdata_complete%20FINAL.ipynb
[2.]: https://github.com/AmeeraArif09/CV-Assignment-3/blob/main/Codes/cvA3self_made_image_augmentation%20FINAL.ipynb
[3.]: https://github.com/AmeeraArif09/CV-Assignment-3/blob/main/Codes/cvA3%20TRANSFER_LEARNING_FINAL.ipynb
[4.]: https://github.com/AmeeraArif09/CV-Assignment-3/blob/main/Codes/CV_A3Transfer_learningaugmented%20Final.ipynb
