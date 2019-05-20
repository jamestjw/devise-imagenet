# DeViSE - ImageNet
We are familiar with how word embeddings map words to an N-dimensional vector space, logically speaking we should be able to do the same with images (assume that we are speaking of images that have one principle object). Hence, if we can map said words and images to the same vector space, we should be able to find interesting relationships.
Here, we shall use the images from ImageNet (since pretrained models are pretrained on this dataset, things are easier for us) and train a neural net that maps images to the same vector space as pretrained word embeddings.

This deep visual-semantic embedding model (DeViSE) leverages textual data to learn semantic relationships between labels, and explicitly maps images into a rich semantic embedding space.
https://papers.nips.cc/paper/5204-devise-a-deep-visual-semantic-embedding-model
