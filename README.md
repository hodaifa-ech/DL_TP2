During this lab, I gained a deeper understanding of the strengths and weaknesses of different deep learning architectures for image classification.  Each part of the lab provided unique insights into the challenges and benefits of different approaches.

**Part 1: CNN and Faster R-CNN, and Fine-tuning**

*   **CNNs:** I learned how to design and train a basic CNN architecture for image classification. CNNs are effective at learning spatial hierarchies and are well-suited for tasks like MNIST. I gained proficiency in defining convolutional layers, pooling layers, and fully connected layers.
*   **Faster R-CNN:** I explored adapting Faster R-CNN for MNIST, which highlighted its complexity and the importance of data preparation. While it achieved reasonable results, I realized it's not the most efficient choice for simple datasets like MNIST due to its object detection focus.  I learned how to format data into 'target dictionaries', and the challenges with this approach.
*   **Fine-tuning:** Fine-tuning pre-trained models like VGG16 and AlexNet proved to be a powerful technique.  Freezing earlier layers and retraining the classifier enabled me to achieve high accuracy with relatively short training times. This section demonstrated the value of transfer learning and the importance of adapting pre-trained models to new tasks.  It illustrated the power of leveraging prior knowledge learned on massive datasets.

**Part 2: Vision Transformer (ViT)**

*   **ViT Implementation:** Implementing the Vision Transformer from scratch was the most challenging part of the lab. I learned how to divide images into patches, project them into embeddings, add positional encodings, and implement the multi-head self-attention mechanism. This required understanding the transformer architecture and its application to images.  The ViT results were initially lower than the CNNs, which emphasized the need for more careful hyperparameter tuning and potentially larger datasets for ViTs to fully realize their potential.
*   **Transformer Concepts:** Gained a grasp on many concepts in transformer models such as the self attention mechanism
