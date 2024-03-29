 # Fine-grained Food Image Classification, Content-Based Image Retrival, Quality Enhancement

The project consists in the development of an application for the recognition of two-dimensional signals (images) of fine-grained food. Specifically we have developed three different tasks:

1. Image pre-processing: pipeline definition for quality improvement
2. Fine-grained food classification
3. Content-Based Image Retrieval, Similarity Retrieval (category search)

## 3. CBIR (category search)

The purpose of the project is to compare three different methods for retrieving the best 5 similar images given a query one.

<img src="images/query_example.jpg" width=640>

Main differences between the methods:

1. CNN as feature extractor using cosine similarity

<img src="images/cnn_architecture.jpg" width=320 height=120>

2. BoWA (Bag of Words using AKAZE descriptors)

<img src="images/akaze_example.jpg" width=320 height=120>

Reference: *Muhammad, Usman, et al. "Bag of words KAZE (BoWK) with two‐step classification for high‐resolution remote sensing images." IET Computer Vision 13.4 (2019): 395-403.*

3. Siamese network trained using triplet loss as feature extractor

<img src="images/triplet_example.jpg" width=320 height=120>


# How to run the code
Unless otherwise specified in the notebook section all codes can be runned in Google Colaboratory platform. All notebooks all already setted to import the necessary packages and also in this way you can easily use a GPU!

# References
[1] Kaur, Parneet, et al. "Foodx-251: a dataset for fine-grained food classification." arXiv preprint arXiv:1907.06167 (2019).

[2] Kupyn, Orest, et al. "Deblurgan-v2: Deblurring (orders-of-magnitude) faster and better." Proceedings of the IEEE/CVF international conference on computer vision. (2019).

[3] Barata, Catarina, M. Emre Celebi, and Jorge S. Marques. "Improving dermoscopy image classification using color constancy." IEEE journal of biomedical and health informatics 19.3 (2014): 1146-1152.

[4] Huang, Shih-Chia, Fan-Chieh Cheng, and Yi-Sheng Chiu. "Efficient contrast enhancement using adaptive gamma correction with weighting distribution." IEEE transactions on image processing 22.3 (2012): 1032-1041.

[5] Chen, Liangyu, et al. "Simple baselines for image restoration." Computer Vision–ECCV 2022: 17th European Conference, Tel Aviv, Israel, October 23–27, 2022, Proceedings, Part VII. Cham: Springer Nature Switzerland, (2022).

[6] Muhammad, Usman, et al. "Bag of words KAZE (BoWK) with two‐step classification for high‐resolution remote sensing images." IET Computer Vision 13.4 (2019): 395-403.
Rego, Joshua D., et al. "Deep camera obscura: an image restoration pipeline for pinhole photography." Optics Express 30.15 (2022): 27214-27235.

# About us

#### Davide Valoti - Data Science Student @ University of Milano-Bicocca
  * [GitHub](https://github.com/valots12)
  * [LinkedIn](https://www.linkedin.com/in/davidevaloti) 
