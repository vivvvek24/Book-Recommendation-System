# Book-Recommendation-System
**AlmaBetter Verfied Project**
![books](https://user-images.githubusercontent.com/100477239/174729861-a8b08d37-fa2c-486c-a789-ae7521af8d62.jpeg)



# 📋 Problem Statement

During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys. In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries). Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create a book recommendation system for users.

## **Content**

The Book-Crossing dataset comprises 3 files.

● Users Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL values.

● Books Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon website.

● Ratings Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

## **Appraoch Pipeline**

Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.

Data Processing: In this part we went through each attributes and encoded the categorical features.

Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

## 💾 **Project Files Description**

This Project includes 1 colab notebook and 1 Pdf of presentation.

### **Executable Files:**
 - Includes Exploratory Data Analysis and all algorithms which are used in this project.

 - Includes pdf of the presentation of the project.

### **Output:**
Google Colab - All the outputs are visible in the provided colab notebook.

## 📋 **Execution Instruction**

The order of execution of the colab notebook is as follows:

1).ipynb

First, click on the open in colab button present on the top center of the notebook.

In this .ipynb file, we have -

• EDA on Book Recommendation system.

• 

• 

**2) Kaggle Dataset**

Downlaod the dataset from kaggle through provided link.Then, connect to the runtime and execute the cell to mount the drive or upload the data file to the current runtime.

**3) Cell Path**

Finally, delete the path in the dataset loading cell and replace it with the path of your current data file. Run each cell to see the output below it.

## **Models Used**

1. Popularity Based Recommendation

2. Model based collaborative filtering

3. Collaborative Filtering-(Item-Item based)

4. Collaborative Filtering-(User-Item based)

## **Conclusions**

1. In EDA, the Top-10 most rated books were essentially novels. Books like The Lovely Bone and The Secret Life of Bees were very well perceived.

2. Majority of the readers were of the age bracket 20-35 and most of them came from North American and European countries namely USA, Canada, UK, Germany and Spain.

3. If we look at the ratings distribution, most of the books have high ratings with maximum books being rated 8. Ratings below 5 are few in number.

4. Author with the most books was Agatha Christie, William Shakespeare and Stephen King.

5. We can conclude that item-item based collaborative filtering performed better than user-user based collaborative filtering because of lower computation among the memory based approach.

6. For modelling, it was observed that for model based collaborative filtering SVD technique worked way better than NMF with lower Mean Absolute Error (MAE).

## **Credits**

Vivek Kumar | Soni Rani

## **References**

Collaborative Filtering documentation - https://realpython.com/build-recommendation-engine-collaborative-filtering/

Popularity based recommendation - https://www.researchgate.net/figure/Architecture-of-the-Popularity-based-Recommender-System_fig2_261199217
