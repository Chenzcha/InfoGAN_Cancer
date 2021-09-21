# InfoGAN_Cancer

Classification of Pancreatic Cancer from Pathological Images using InfoGAN-based Unsupervised Learning

We assumed pancreatic cancers can be categorized different severity level.
This work tried to use InfoGAN (mutual information + GAN) to disentangle the latent representation of pancreatic cancer images. 
That is, a new case can be automatically detected the cancer severity and the results could support the clinical decision.
Here, the multi-resolution CNNs are used for mappingt the feature while the SENet can exhibit the channel attention. The mutual information + GAN module is adopted to explore the latent space and the number of subspace.

The implementation can be found in file, InfoGAN 128 with Classifier.ipynb (Inception+SEnet+InfoGAN)

The evaluation and visualization have shown in file, numpy to heatmap 128 kmean Incep 3cla.ipynb


Result:

Cancer image generation by the proposed method:

![generated-10-1000](https://user-images.githubusercontent.com/34312998/133878575-20612d13-9d4f-4a96-aa4b-0cefa94f1a26.png)

Clustering result:

<img width="503" alt="image" src="https://user-images.githubusercontent.com/34312998/133878686-de407e15-f7d5-40aa-be16-26bc46e110d2.png">


Reconstructtion and Visualization results:

<img width="502" alt="image" src="https://user-images.githubusercontent.com/34312998/133878714-68185845-5192-4905-a807-496b9370675e.png">
