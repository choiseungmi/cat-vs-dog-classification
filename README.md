# cat-vs-dog-classification

### Data
Download data from: https://www.kaggle.com/c/dogs-vs-cats/data  
Image training set contain 12500 images for each category.  
I split those into 80% train and 20% means validation.

Folder structure
```
# base path : content/gdrive/My Drive/
# project path(current path) : base path / Colab Notebooks/cat_and_dog_classification/

./dogs-vs-cats/
    train/
        ### dogs 12500 pictures
        dog001.jpg
        dog002.jpg
            ...
        ### cats 12500 pictures
        cat001.jpg
        cat002.jpg
            ...
    test1/
        ### 1597 pictures
        dog001.jpg
        dog002.jpg
        ...
        cat001.jpg
        cat002.jpg
```

### Dependencies
  `colab`
  `Tensorflow 1.14`
  `Python 3.6`
  `Matplotlib`
  `Seaborn`
  `Scikit-Learn`
  `Pandas`
  `Numpy`
