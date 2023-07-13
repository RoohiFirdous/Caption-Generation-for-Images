# Caption-Generation-for-Images
Image captioning can help in many real-world applications such as image search, providing a description of visual content to users with visual impairments, allowing them to better understand the content
I have used vision Transformer in this development, the idea of Vision Transformer architecture is that it splits the image into fixed-size patches, which are flattened and then lower-dimensional linear embeddings are created from these patches. This way, it will behave as if it's a sequence of text.
We will use Vision Encoder-Decoder architecture models, where the encoder is the ViT or Swin, and the decoder is a language model such as GPT2 or BERT.
The dataset used in image captioning is the Common Objects in Context (COCO). We'll be using the 2014 version of it which contain more than 500,000 images and their descriptions.
I've  trained the model using the COCO dataset using the Trainer class and also using PyTorch training loop.
