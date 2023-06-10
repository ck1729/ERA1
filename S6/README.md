# Session 6
<p> A Simple Neural Network to achieve 99.42% accuracy on MNIST using 
  Pytorch </p>

#### Description of the Network and Training:
1. Import the required libraries of Pytorch
2. Network has 3 Convolution block with 2 Max Pooling Layers
3. Global Average Pooling has been instead FC layer
4. Total Number of parameters : <b> 15,674 </b>
5. Number of Epochs: <b> 20 </b>
6. Data Augmentation:

    <I> transforms.RandomAffine(degrees=10, translate=(0.1,0.1), scale=(0.9, 1.1)),
    
  transforms.ColorJitter(brightness=0.2, contrast=0.2) </I>

7. Basic Architecture of each block: <b> CONV >> RELU >> BN >> Maxpool >> Dropout </b>
8. Dropout value of 0.2 was used
10. Each Epoch took <b> ~45seconds </b> to train on GPU
11. Test Accuracy: <b> 99.42 </b>

