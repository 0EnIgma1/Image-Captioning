# Image-Captioning
A Deep Learning Model comprises of CNN and Attention Transformers to understand what's happening in an image and generate Captions for images

The model is trained on 'Flickr8k' dataset.

workflow:
- The image is passed onto 'EfficientNet' CNN model to extract the image features
- The features are passed into Transformers Encoder to get new representation of the features
- Encoder output is passed into Transformers Decoder along with text sequences to generate new captions

  
<p align = "center">
  <img width = 800 src = "https://github.com/0EnIgma1/Image-Captioning/blob/main/roadmap.png"
</p>
> - A roadmap to visualize my process of building this Model.
