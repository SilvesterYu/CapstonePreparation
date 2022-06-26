# Transformer Notes

Notes taken from [this article](https://www.louisbouchard.ai/will-transformers-replace-cnns-for-vision/)

### Attention
In NLP, attention is basically measuring how each word in the input sentence is associated with each word on the output translated sentence. Similarly, there is also what we call self-attention that could be seen as a measurement of a specific word’s effect on all other words of the same sentence. 

In computer vision, this same process can be applied to images calculating the attention of patches of the images and their relations to each other,

The computational complexity of its self-attention is quadratic to image size.

