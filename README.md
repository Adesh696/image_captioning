<h1>Image Captioning</h1>

Image captioning is the task of predicting a caption for a given image. Common real world applications of it include
aiding visually impaired people that can help them navigate through different situations. Therefore, image captioning
helps to improve content accessibility for people by describing images to them.

Before you begin, make sure you have all the necessary libraries installed:

```bash
pip install transformers datasets evaluate -q
pip install jiwer -q
```

Model : [microsoft/git-base](https://huggingface.co/microsoft/git-base)

Dataset : [Naveengo/flickr8k](https://huggingface.co/datasets/Naveengo/flickr8k)

