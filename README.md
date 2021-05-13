# deep_learning_Image_caption_generator
Image Caption Generation using Deep Learning
Dataset: To get flickr8k dataset, please fill out this [form](https://forms.illinois.edu/sec/1713398)

Experiments:
I have carried out different experiments, 
1. Extracting features from vgg16, inceptionv3, and Xception model and then tokenizing the captions of all the images.
2. I tired using pretrained glove vectors in the embedding layer of the model by creating a matrix that contains the caption words and their relevant weights from glove vectors.
However, I tried out the models by overriding the same cell and making changes like different epochs and batch size on the same cell. So the results that I have given in report might be missing for some experiments since I have overriden it. So I have given the actual file where I captured the results for report, and another file which holds all the models, and their results, which I created to upload in github.
The file pointing to this experiment will be (Image_caption_generation_results_shown_in_report(with glove vectors).ipynb). This will have results shown in report.
(Image_caption_generation_results_shown_in_report(without glove vectors).ipynb). This will have the results shown in report.

3. Deep_learning_image_caption_generation_with_word_embeddings_glove.ipynb. This file will contain all the models and their relevant results. And this model uses glove vectors.
4. Deep_learning_image_caption_generation_without_word_embeddings_glove.ipynb. This file will contain all the models and their relevant results without the usage of glove vectors.

5. Another experiment was carried out using limiting the vocab size by taking only the caption words that occurs more than 10 times in the entire vocabulary of captions.
(Model_using_limited_vocab_size.ipynb). This file contains the model that runs with limited vocab size.
