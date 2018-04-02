# Word Cloud
* A Word Cloud made with a couple Python packages.  
* I used a Virtual Machine (VMware) to install packages and run Jupyter Notebook.  Since I have a Windows computer I do not have Linux directly on my computer.   

## Word Cloud of the Adventures of Sherlock Holmes 
By Sir Arthur Conan Doyle

We can first analyze the frequencies of words using by creating a simple program in Python to count the number of each word.  This is shown in the file: [Click Here](https://github.com/sitarobinson/Word-Cloud/blob/master/The%20Adventures%20of%20Sherlock%20Holmes%20Frequency%20Counter.ipynb)

## Word Cloud without Check for Stopwords
* The common words are the biggest in the word cloud.  
* These are the default colors for a word cloud.

![](https://github.com/sitarobinson/Word-Cloud/blob/master/sherlockholmes.png)

## Word Clouds with Common Stopwords Removed 
* Commonly when I think of Sherlock Holmes I think of everything in grayscale or black in white.  
* I will also remove the common stopwords which are words that really do not have much meaning and that are very common in almost every text.   

## Masked Word Cloud
* We can also do something called masking which uses an image and constrains the distribution of words.  This technique makes the word cloud in the shape of the image.  For this example I've decided to use this image which is the silhouette of Sherlock Holmes: 

<p align="center"><img src="https://github.com/sitarobinson/Word-Cloud/blob/master/sherlock.jpg" width="360" height="345"></p>
