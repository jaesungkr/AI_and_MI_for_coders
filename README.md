# AI and Machine Learning for Coders: Study Notebooks

Personal study notebooks following *AI and Machine Learning for Coders*. The repository contains hands-on TensorFlow/Keras exercises with Korean notes, covering computer vision and text preprocessing.

## Notebooks

| Notebook | Topics |
| --- | --- |
| [Chapter 3: Computer vision](3%E1%84%8C%E1%85%A1%E1%86%BC_%E1%84%80%E1%85%A9%E1%84%80%E1%85%B3%E1%86%B8_%E1%84%8F%E1%85%A5%E1%86%B7%E1%84%91%E1%85%B2%E1%84%90%E1%85%A5_%E1%84%87%E1%85%B5%E1%84%8C%E1%85%A5%E1%86%AB_%E1%84%8B%E1%85%B5%E1%84%86%E1%85%B5%E1%84%8C%E1%85%B5%E1%84%8B%E1%85%A6%E1%84%89%E1%85%A5_%E1%84%90%E1%85%B3%E1%86%A8%E1%84%8C%E1%85%B5%E1%86%BC_%E1%84%80%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%B5%E1%84%92%E1%85%A1%E1%84%80%E1%85%B5.ipynb) | Horse-or-human image classification, convolutional networks, data augmentation, and transfer learning with InceptionV3. |
| [Chapter 5: Natural language processing](5%E1%84%8C%E1%85%A1%E1%86%BC_%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AB%E1%84%8B%E1%85%A5_%E1%84%8E%E1%85%A5%E1%84%85%E1%85%B5_%E1%84%89%E1%85%A9%E1%84%80%E1%85%A2.ipynb) | Tokenization, out-of-vocabulary tokens, padding, `TextVectorization`, and IMDb text preprocessing. |

## Using the notebooks

Open the notebooks in Jupyter or Google Colab and run the cells in order. They use TensorFlow/Keras, NumPy, Matplotlib, TensorFlow Datasets, and Beautiful Soup; the Colab sample-image fallback also uses gdown.

The vision notebook downloads training images and pretrained weights. Local prediction cells expect `hh_image_1.jpg` through `hh_image_3.jpg`, while the Colab path supports uploaded or downloaded examples. The NLP notebook downloads IMDb data through TensorFlow Datasets.

These are historical learning notes using APIs such as `ImageDataGenerator`, `Tokenizer`, and the IMDb subword encoder. Package versions are not pinned, so some cells may need adaptation in a current environment.

## Learning resources

The notebooks reference Laurence Moroney's horse-or-human datasets and the [Korean companion examples](https://github.com/rickiepark/aiml4coders). They are a personal learning record, not an original framework or a complete reproduction of the book.

![Book cover](https://user-images.githubusercontent.com/82886701/210038813-13ae860f-5cc3-4eee-b6da-9aa23a922101.png)
