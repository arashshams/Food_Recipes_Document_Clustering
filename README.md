# Food_Recipes_Document_Clustering
This repo hosts an Unsupervised Machine Learning [model](https://github.com/arashshams/Food_Recipes_Document_Clustering/blob/master/Analysis.ipynb) for [Doument Clustering](https://en.wikipedia.org/wiki/Document_clustering) on [Kaggle's Food.com recipes corpus](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions). This corpus contains 180K+ recipes and 700K+ recipe reviews, however in this analysis I will only focus on recipes and not on recipe reviews.

**Note:** The data set is not included in this repo due to size limitations. Make sure to dowanload the data (`RAW_recipes.csv`) from Kaggle and put it in the project root.

The goal is to extract main categories or groupings of recipes based on their names.

You can also check the Kaggle Kernel for this notebook [here](https://www.kaggle.com/code/arashshamseddini/document-clustering-on-food-recipes).

### Dependencies

If you want to reproduce the [report](https://github.com/arashshams/Food_Recipes_Document_Clustering/blob/master/Analysis.ipynb) (`Analysis.ipynb`) on your local, simply run below commands in terminal to create the environment for running the notebook.

```
conda env create -f environment.yaml
conda activate env
```
