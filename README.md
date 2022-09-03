
# BOOK RECOMMENDATION SYSTEM
These project is part of the “Machine Learning &Advanced Machine Learning” curriculum as capstone projects at [AlmaBetter](https://www.almabetter.com/). 

#### -- Project Status: [Completed]

## Objective<br>
The main objective is to create a book recommendation system for users. Recommender systems are really critical in some industries as they can generate a huge
amount of income when they are efficient or also be a way to stand out significantly from competitors. 

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes 1 executable files and 1 project documentation  as follows:</p>
<h4>Executable Files:</h4>
<ul>
  <li><b>Book_Recommendation_System.ipynb</b> - Complete notebook containing Data exploration/Data processing/transformation/model development.</li>
</ul>


<h4>Documentation:</h4>
<ul>
  <li><b>Book_Recommendation_System_cohort_nilgiri.docx</b> - Includes the documentation of the project.</li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### Methods Used
* Descriptive Statistics
* Data Visualization
* Machine Learning


### Technologies
* Python
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-learn
* Surprise

### Data
The Book-Crossing dataset comprises 3 files.
* Users : 
Contains the users. Note that user IDs (User-ID) have been anonymized and map to
integers. Demographic data is provided (Location, Age) if available. Otherwise, these
fields contain NULL values.
* Books : 
Books are identified by their respective ISBN. Invalid ISBNs have already been removed
from the dataset. Moreover, some content-based information is given (Book-Title,
Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web
Services. Note that in the case of several authors, only the first is provided. URLs linking
to cover images are also given, appearing in three different flavors (Image-URL-S,
Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the
Amazon website.
* Ratings :
Contains the book rating information. Ratings (Book-Rating) are either explicit,
expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit,
expressed by 0.

## Project Description
* EDA - Performed exploratory data analysis on numerical and categorical data.
* Data Cleaning - Missing value imputation,Outlier Treaatment
* Feature Selection - Used User-ID,ISBN and Books-Rating for model development.
* Model development - Tried Popularity based model and Collaborative filtering (Both Memory based and Model based).

## Memory Based Collaborative Filtering
Memory-based methods use user rating historical data to compute the similarity between users or items. The idea behind these methods is to define a similarity measure between users or items, and find the most similar to recommend unseen items.

## Model Based Collaborative Filtering
Model-based CF uses machine learning algorithms to predict users rating of unrated items. There are many model-based CF algorithms, the most commonly used are matrix factorization models such as to applying a SVD to reconstruct the rating matrix, latent Dirichlet allocation or Markov decision process based models.

Refer this [**blog**](https://towardsdatascience.com/how-does-collaborative-filtering-work-da56ea94e331) for more information on collaborative filtering

## Needs of this project

- data exploration
- data processing/cleaning
- recommendation system developer


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Execution Instruction</h2>
<p>The order of execution of the program files is as follows:</p>
<p><b>1) Book_Recommendation_System.ipynb </b></p>
<p> The Book_Recommendation_System.ipynb contains the entire code for Data exploration/Data processing/transformation/model development </p>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

🚀 About Me


- 👋 Hi, I’m Abhishek, a curious Data Scientist
- 👀 I’m currently working on Machine Learning projects.
- 🌱 I’m currently learning various machine learning models and deep learning techniques.
- 💞️ I’m would love to collaborate on Machine Learning projects.
- 📫 How to reach me : abhishekanand3120@gmail.com
- 👀 LinkedIn : https://www.linkedin.com/in/abhshkannd/
