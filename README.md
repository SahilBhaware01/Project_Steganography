# Project_Steganography
Steganography Leveraging Generative Adversarial Networks

As part of my coursework, I dove into the intriguing domain of steganography, exploring how hidden data can be embedded and detected within images. Leveraging Generative Adversarial Networks (GANs), this project aims to push the boundaries of digital security and image processing.

Problem Statement:
Traditional methods of image steganography hides secret informaton in images acting as carriers, which are left with subtle traces. Machine learning-based steganalysis programs are developed which can tell the diﬀerences between original and modified images quite easily. This vulnerability makes the secret communication both insecure and detectable. To solve this, the project proposes a method named Steganography Without Embedding (SWE) using DeepConvolutional Generative Adversarial Networks (DCGANs) to create carrier images from scratchwithout any detectable traces and still allows secure and good informa=on retrieval.

📌 Dataset: CelebFaces Attributes (CelebA) Dataset
  Large-Scale & Labeled: Contains 200,000+ celebrity images with 40 facial attributes per image, ideal for facial recognition and attribute prediction tasks.
  Diverse Conditions: Offers images with varied poses, backgrounds, and landmarks, providing robust training data for deep learning models.
  Download Link: https://www.kaggle.com/datasets/jessicali9530/celeba-dataset

📌 Project Breakdown
  Phase 1: Developing a DCGAN with a generator and discriminator and training both models in adversarial loop to produce realistic cover images.
  Phase 2: Designing and training an extractor to decode hidden messages by retrieving encoded noise vectors from steganographed images.
  Phase 3: Building an encoder at the sender’s end for embedding hidden data and a decoder at the receiver’s end for accurate retrieval.

📌 Key Challenges & Solutions:

  Challenge: Limited computing power and lack of TPUs led to longer training times and slower experimentation.
  Solution: Optimized model parameters and used GPU resources efficiently to maintain project progress.
  Learning Curve with GANs:

  Challenge: Initially struggled with GAN concepts and model stability.
  Solution: Overcame this through extensive research, implementing model checkpoints, and experimenting with hyperparameters.
  Handling Large Datasets:

  Challenge: The extensive CelebA dataset required significant processing power and extended training epochs.
  Solution: Preprocessed and reduced the dataset while maintaining data integrity, enabling manageable training within resource constraints.

Generated images 

<img width="513" alt="Screenshot 2024-11-20 at 12 07 49 PM" src="https://github.com/user-attachments/assets/45798b8f-79fd-472e-a018-8e655a3ba74a" />

Conclusion:
This project demonstrated the use of GANs in steganography, creating undetectable images for secure data embedding. I learned how to train and optimize DCGANs, handle large datasets, and address challenges like model stability and computing limitations.

Enhancements and Future Scope:
Future improvements could involve using VAEs or Transformer-based GANs for better security and extending the method to video steganography with 3D GANs.

Real-Time Applications:
This approach has applications in secure communication, digital watermarking, forensic analysis, and secure data sharing, making it highly relevant for digital security.
