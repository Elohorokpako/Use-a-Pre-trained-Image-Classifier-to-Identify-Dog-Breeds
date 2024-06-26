# Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds
This is a Udacity-Guided project where I compared three classifiers: alexnet, rexnet and vgg in classifying dogs and dog breeds.

First, clone the repo into your local machine
```{r}
git clone https://github.com/Elohorokpako/Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds.git
```
### Requirements
You need to install pytorch to be able to run the codes. you can install pytorch separately or alternatively create a new environment using the environment.yml file, and install all requirements

You can install pytorch with pip
```{r}
pip install pytorch
```
or,

create a new environment using the environment.yml file and install all requirements
```{r}
conda env create -f environment.yml
```
Activate the environment.
```{r}
conda activate myenv
```
### Usage
Upload the images you wish to classify on the **uploaded_images** folder.
When uploading the dog images, follow the naming format:

animal_name_01.jpg, with names separated by underscores.

Check the **pet_images** folder to see examples of how the animals are named.

To classify the dogs, run the code
```{r}
sh run_models_batch_uploaded.sh 
```
### Results
Check the **alexnet_uploaded-images.txt**, **resnet_uploaded-images.txt**, and **vgg_uploaded-images.txt** to see the results of the classification

If you wish to see the results of the classification of the **pet_images** rather, run the codes
```{r}
sh run_models_batch.sh 
```
and check the **alexnet_pet-images.txt**, **resnet_pet-images.txt**, and **vgg_pet-images.txt** to see the results of the classification of the **pet_images** folder

To view the results on the terminal for the classification of the **pet_images**, run
```{r}
python check_images.py 
```
