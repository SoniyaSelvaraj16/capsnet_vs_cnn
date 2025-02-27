# CapsNet vs CNN: Image Recognition on MNIST  

## Project Overview  
This project compares Capsule Networks (CapsNet) and Convolutional Neural Networks (CNN) for image recognition using the MNIST dataset. While CNNs are widely used for image classification, they struggle with preserving spatial relationships. CapsNet, introduced by Hinton et al., aims to overcome this limitation by maintaining spatial hierarchies using dynamic routing.  

## Key Objectives  
- Implement CapsNet and CNN models.  
- Train both models on the MNIST dataset.  
- Evaluate their performance based on accuracy, training time, and robustness to transformations such as rotation and shifts.  
- Analyze whether CapsNet provides advantages over traditional CNNs in handling spatial hierarchies.  

## Experiment Overview  
The MNIST dataset consists of 28x28 grayscale images of handwritten digits from 0 to 9. The project involves:  
- Designing and implementing a **CapsNet** model using TensorFlow, including convolutional layers, capsule layers, and dynamic routing.  
- Implementing a **CNN** model with convolutional layers, pooling layers, and fully connected layers for comparison.  
- Training both models using the Adam optimizer and evaluating their performance based on classification accuracy and robustness to image transformations.  

## Results  
CapsNet demonstrated competitive accuracy compared to CNNs but required more computational resources and training time. However, it outperformed CNNs in recognizing rotated and transformed images, highlighting its ability to preserve spatial hierarchies. CNNs, while efficient and faster to train, struggled with maintaining spatial relationships.  

## Conclusion  
The project highlights the strengths of CapsNet in handling spatial transformations while also identifying its computational limitations. While CNNs remain a strong baseline for image classification, CapsNet shows potential for applications requiring better spatial awareness.  

