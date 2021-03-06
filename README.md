<h1 align="center">
  <img src="https://www.thehindu.com/opinion/op-ed/x9sol6/article29451786.ece/ALTERNATES/FREE_960/Fake-news" height="200px" width="200px" alt="FAKE NEWS"><br>
  Fake News Detection
</h1>

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/Manimaran-SM/Fake_News_Detection/blob/master/LICENSE)

* [Overview](#Overview)
   * [Introduction](#Introduction)
   * [Why?](#Why_this_Algorithm)
   * [Challenges Faced](#Challenges_Faced)
   * [Limitation](#Limitation)
   
* [Guide](#Guide)
  * [System Configuration](#System_Configuration)
  * [Procedure](#Procedure)
  * [Pre-requisite](#Prerequisite)
  * [Dataset](#Dataset)


# Overview:
## Introduction
>* Fake news is a major concern in our society right now. It has gone hand-in-hand with the rise of the data-driven era – not a coincidence when you consider the sheer volume of data we are generating every second! Fake news is such a widespread issue that even the world’s leading dictionaries are trying to combat it in their own way.
>* I’ve been working in the Machine learning (ML) space and so i proposed a system which would analyze the fake news using classification algorithm and report it back 

## Why_this_Algorithm
  >* I used Passive Aggressive Classifier. Passive-aggressive classification is one of the available incremental learning algorithms and it is very simple to implement, since it has a closed-form update rule.
  >* refer this for detailed description [passive_aggressive_classifier](https://www.bonaccorso.eu/2017/10/06/ml-algorithms-addendum-passive-aggressive-algorithms/)
  >* Here is another two key terms "Term frequency and inverse document frequency". 
  <br>Term Frequency measures the frequency of a word in a document. This highly depends on the length of the document and the generality of word. 
  <br>```tf(t,d) = count of t in d / number of words in d ```
  <br>DF is the number of documents in which the word is present. IDF is the inverse of the document frequency which measures the informativeness of term t.
  <br>```df(t) = occurrence of t in documents```
  <br>```idf(t) = N/df```
  

## Challenges_Faced
  >* I found it hard working with the data extraction feature. Since the version varied it kind of affected the required accuracy of the system.
  >* Kindly refer this documentation [TFIDFVectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html) and understand the parameters before using it in your system. 

## Limitation
  >* It requires more understanding of the dataset  

# Guide:
## System_Configuration
>* Graphic card: NVIDIA GeForce GTX1050
>* CPU: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
>* RAM: 8GB
>* Disksapce: 1TB

## Procedure
>* Click clone/download
>* If you github desktop click open in desktop hit the clone button. 
>* If you use download zip, then extract the zip file  
>* If you want to use HTTPS say (https://github.com/Manimaran-SM/Fake_News_Detection.git),  then use the command
``` 
$ git clone https://github.com/Manimaran-SM/Fake_News_Detection.git
```
>* After completing the above steps, You must have anaconda or jupyter notebook to execute this code.
>* Now run the [file1.pynb](https://github.com/Manimaran-SM/Fake_News_Detection/blob/master/file1.ipynb) file. You wil get output as shown in the above file.
>* If you have any problems regarding this repository while opening feel free ask me [here](https://github.com/Manimaran-SM/Fake_News_Detection/issues/new)
### Note:
>* If you have problem related with git command refer this documentation [link](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)

## Prerequisite
Install Numpy with:

```
pip install numpy
```
Install Pandas with:

```
pip install pandas
```
Install Sklearn with:

```
pip install scikit-learn
```
## Note:
>* Given commands works only for windows.
>* Python IDE and Following packages must be installed in system.
    
## Dataset
>* Refer in this repostory or click here [news.csv](https://github.com/Manimaran-SM/Fake_News_Detection/blob/master/news.csv)

