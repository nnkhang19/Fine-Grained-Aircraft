# Fine-grained Image Classification

## Dataset
- Due to constraints in file size, I cannot upload the dataset to this repo. 
- You may need to download the dataset from [here](https://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/) and locate it in the same directory with this repo.
- The csv files contain all information needed to load the data in my pipeline, including image file, bounding box, manufacturer, and variant.
## Source code
- Since I used google colab for this project, all of my source code are written in notebook files as follows:
  - **data.ipynb**: this file is used for data preprocessing and generating csv files.
  - **variant_classification.ipynb**:  you can find all code relating to model, data loader, and training functions in this file. 
