# Pima Indians diabetes analysis
## Description
This project aims to look into the diabetes data of Pima Indians using R Programming. Through the use of diabetes data and machine learning models, it can help us to explore the correlation between variables and determine significant factors contributing to diabetes. Every aspect of this project is a sample code which shows how to do the following:

* Data cleaning and transformation 
* Preliminary Exploratory Analysis of each variable and  
* Exploring and comparing the performance of different machine learning techniques for prediction and classification 

For full documentation, view [here](https://seeying147.github.io/pimaindians-diabetes-analysis/)

## Dataset
The dataset can be found in RStudio by running the following code:
```{r}
data("PimaIndiansDiabetes")
```

## Technologies Used
The project is created with RStudio v4.1.2 (Install [here](https://posit.co/products/open-source/rstudio/))

## Setup
To run this project:
* Run data("PimaIndiansDiabetes") to view the original dataset
* Download index.Rmd and open the document in RStudio
* In RStudio, install 9 packages using the following command:
```{r}
install.packages(mlbench)
install.packages(ggplot2)
install.packages(corrplot)
install.packages(dplyr)
install.packages(caret)
install.packages(gridExtra)
install.packages(VIM)
install.packages(class)
install.packages(e1071)
``` 
* Click "Knit" to view the project. 

## License
This project is licensed under MIT License- see LICENSE file for details

