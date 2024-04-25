# Birds_CNN_PyTorch
Learning project for school. </br>
Idea is to present your work in detail to other students in the course. 

## CNN Architecture
EfficientNet-B4 (pretrained)

## Data
High quality birds dataset from kaggle: https://www.kaggle.com/datasets/gpiosenka/100-bird-species/data
* 525 bird species -> reduced to 184 (Only bird names starting with A,B or C) 
* 84635 training img -> reduced to 29274
  * Each species has at least 130 training imgs
  * ~80% Male and 20% female, this is a shortcoming in the dataset   
* 2625 test & validation imgs (~3% each, very low IMO) -> reduced to 920
* 224x224x3 JPG

## Approach
Data is prepared, we can go almost straight into modeling and evaluation. </br>
Plan is to make a nice well explained Jupyter Notebook that can be presented live (except the training of course) </br>
* Save the model
* Explain everything
* Visualizations

<b>Note:</b> Again, this is a learning project. Never coded PyTorch myself before this. </br>
Materials I've used so far:
* https://pytorch.org/tutorials/beginner/basics/quickstart_tutorial.html (Low complexity)
* https://www.kaggle.com/code/ibrohimsharipov/birds-classification-pytorch-96-accuracy (Easy to follow)
* https://www.kaggle.com/code/harpdeci/classifying-birds-with-resnet (This one pretty advanced)
* ChatGPT4 (no copypasta code, just further explain some concepts for me)
* Google search


