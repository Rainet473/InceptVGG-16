# InceptVGG-16
Attempted to create a CNN model that replicates the VGG-16 model but instead of simple convolution layers, the layers with 256 and 512 filters as output were converted into basic Inception module layers.\n 
Data Augmentation was also used in the Kaggle Dataset.\n
The model can classify between cats and dog with a validation accuracy of around 94%.\n
Refer to the jupyter code or the Kaggle Link : \n
https://www.kaggle.com/code/arijeetpramanik/vgg-16-model-design-with-inception-blocks \n
\n
NOTE: If you refer to the sample results on testing in the provided jupyter file. There is only one error where the model predicts the image containing dog instead of cats. The reason is highly likely due to the doll of dog present in the image being more clearly visible than the cats.
