
# Image Captioning


## Dataset:Flickr8k

- Flickr8k Dataset: This dataset contains 8,000 images, each paired with five descriptive captions. It is widely used in image captioning research due to its diverse and rich annotations.

## Encoder: ResNet50

- For the encoding phase, we employed ResNet50, a powerful convolutional neural network (CNN) pre-trained on ImageNet. ResNet50 is renowned for its deep architecture, which allows it to capture intricate patterns and features in images.By leveraging a pre-trained model, we benefit from the transfer learning capabilities, improving the model's performance on the image captioning task.

## Decoder: Transformer

- For the decoding phase, we implemented a Transformer-based model. Since Transformers do not have a built-in sense of sequence, we incorporated positional embeddings to provide the model with information about the position of each word in the sequence.


## Related

Here are some readings

[ResNet](https://wandb.ai/mostafaibrahim17/ml-articles/reports/The-Basics-of-ResNet50---Vmlldzo2NDkwNDE2)

[Transformers](https://towardsdatascience.com/are-transformers-better-than-cnns-at-image-recognition-ced60ccc7c8)

Dataset

[Flickr8k](https://www.kaggle.com/datasets/adityajn105/flickr8k)
## Results
<img align="right" height="120" src="https://github.com/victorgearhead/Image_Captioning/blob/main/SCs/Screenshot%202024-06-17%20155744.png"  />
![Screenshot](https://github.com/victorgearhead/Image_Captioning/blob/main/SCs/Screenshot%202024-06-17%20155744.png)

![Screenshot](https://github.com/victorgearhead/Image_Captioning/blob/main/SCs/Screenshot%202024-06-17%20155805.png)

![Screenshot](https://github.com/victorgearhead/Image_Captioning/blob/main/SCs/Screenshot%202024-06-17%20155814.png)

![Screenshot](https://github.com/victorgearhead/Image_Captioning/blob/main/SCs/Screenshot%202024-06-17%20155821.png)



## Author

- [@BhalaVignesh](https://github.com/victorgearhead)

