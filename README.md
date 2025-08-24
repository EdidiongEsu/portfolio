# My Portfolio

![](https://github.com/EdidiongEsu/portfolio/blob/master/img/Capture.PNG)

# 👋 Hi, I’m Edidiong  
### Experienced Data & Analytics Engineer | Building Scalable, Insightful Data Systems

I have over 5 years of experience delivering end-to-end data solutions, from architecting robust data pipelines and transforming raw datasets into clean, tested models, to enabling fast, reliable analytics that support critical decision-making.

My work bridges engineering precision with business context, ensuring that data systems are not only technically sound but also aligned with real-world goals. I’ve led initiatives across the full data lifecycle and thrive in roles where I can design, build, and scale modern data infrastructure.

I'm open to opportunities in **analytics engineering**, **data engineering**, or **senior analytics**, where I can apply my full-stack data expertise to drive meaningful, data-informed outcomes.

## Databricks Certified Data Engineer Associate

I’m certified as a **Databricks Data Engineer Associate**, demonstrating practical expertise in building and maintaining data workflows on the Databricks Lakehouse Platform.

<p align="center">
  <a href="https://credentials.databricks.com/d07ac3d4-eda6-4706-849e-4bf87932052a#acc.x03av9uO" target="_blank">
    <img src="https://github.com/EdidiongEsu/portfolio/blob/master/img/Databricks%20Certified%20Data%20Engineer%20Associate_page-0001.jpg?raw=true" alt="Databricks Certified Data Engineer Associate Badge" width="250"/>
  </a>
</p>

🔗 [**View Certification on Databricks Credentials**](https://credentials.databricks.com/d07ac3d4-eda6-4706-849e-4bf87932052a#acc.x03av9uO)


## My Past Projects
---
### [Earthquake Data Pipeline with Databricks](https://github.com/EdidiongEsu/Databricks_earthquake)

This project showcases a scalable data pipeline built using Databricks and the medallion architecture (bronze, silver, gold) to process earthquake data. The goal is to efficiently ingest, transform, and analyze real-time earthquake data from the USGS API and store it in structured Delta Lake tables for downstream analytics.

Key deliverables include setting up an automated ingestion process, implementing transformations at each layer, and ensuring that the final dataset is ready for analysis and visualization.

More details and full implementation available [here](https://github.com/EdidiongEsu/Databricks_earthquake).


#### Data Architecture

The workflow and tools used in the project follow a medallion architecture pattern:

![Databricks Earthquake Pipeline](https://github.com/EdidiongEsu/Databricks_earthquake/blob/main/img/Earthquake%20architecture.gif)

---
### [End-to-End Data Engineering Project: Capital Bikeshare](https://github.com/EdidiongEsu/capital_bikeshare)
This project involves extracting, moving, and analyzing data from Washington DC's Capital Bikeshare system to uncover key insights. By implementing an end-to-end data pipeline, it aims to efficiently process data, store it in an analytical warehouse, and create an interactive dashboard for easy decision-making. Key deliverables include developing a robust data pipeline, managing its resources and designing the interactive dashboard. More details [here](https://github.com/EdidiongEsu/capital_bikeshare)

#### Data Architecture
The workflow, tools, and implementation of the project are summarized in the project architecture below:
![Alt text](https://github.com/EdidiongEsu/capital_bikeshare/blob/main/img/Bike%20architecture.gif)

---
### [Car Image Prediction service using deep learning](https://github.com/EdidiongEsu/mlzoomcamp_capstone_one)
An interactive car image prediction service where pictures can be uploaded and classified. It can be viewed by clicking <b>*[this link](https://edidiongesu-mlzoomcamp-capstone-one-main-app-uy4dzl.streamlit.app/)*</b>

Here is the interface:
    ![](https://github.com/EdidiongEsu/mlzoomcamp_capstone_one/blob/main/images/webapp.png)

Upload an image:
    ![](https://github.com/EdidiongEsu/mlzoomcamp_capstone_one/blob/main/images/webapp2.png)

Classify the car image:
    ![](https://github.com/EdidiongEsu/mlzoomcamp_capstone_one/blob/main/images/webapp3.png)

---
### [Similarity between Genres by analyzing 1.12Million words contained in blurbs using Natural Language Processing](https://github.com/EdidiongEsu/genre_NLP)


<p align="center"> 
<img src="https://github.com/EdidiongEsu/portfolio/blob/master/img/common_nlp_gif.gif" />
</p>

I analyzed blurbs of over a million words to check for similarity between genres. A blurb is a short (usually about 200 words) description of a book written for promotional purposes. I ascertained if blurbs are accurate representations of whole books by checking for frequencies of words in each genre. Deductions were made which gave an insight into the writing style of african literature. The data used in this repository was scraped from Africa's most popular e-store by my [webcrawler](https://github.com/EdidiongEsu/okadabooks_scraper). 

[Jaccard similarity](https://en.wikipedia.org/wiki/Jaccard_index) was used to calculate the similarity metric by comparing word types across genres and the visulization was done with a donut plot.
    
   
  
  ---
 ### [Scraping and analyzing of okadabooks](https://github.com/EdidiongEsu/analyzing_okadabooks)
![](https://github.com/EdidiongEsu/portfolio/blob/master/img/double_header.PNG)
[Okadabooks](https://okadabooks.com/) is an online store of e-books dedicated to african literature. It is one of Africa's most largest platform with about 330,000 users and 500Milion pages read annually. 
The purpose of this project was to look into the reading patterns of  okadabooks readers from when it was founded in 2013. For self-publishing authors (Like myself), I generated a success metric for its authors and checked the frequency at which books were purchased from okadabooks. I wrote about my findings and insights [here](https://towardsdatascience.com/riding-okadabooks-aae359d9fbad)

The scraping of okadabooks involved combining the powerful libraries of selenium,request and BeautifulSoup. Selenium was used because of the dynamic content of the store. Scraping involved tapping LoadMore Pagination while ensuring to imitate user usage. More details on the webcrawler [here](https://github.com/EdidiongEsu/okadabooks_scraper).


 ---
### [Child Mortality in Nigeria](https://github.com/EdidiongEsu/child-mortality/blob/master/README.md)
<p align="center"> 
<img src="https://github.com/EdidiongEsu/portfolio/blob/master/img/child_mortality.jpg" width="400px" height="300px" />
</p>

This is mortality based analysis that focuses on the trend of child death from malaria in Nigeria and its neighbouring countries with respect to the whole world . Data was gotten from [UNICEF](https://data.unicef.org/). I looked into neonatal and post-neonatal deaths in a bid to see if the right steps had been taken into eliminating natal deaths. Comparisons were made with neighbouring countries and deductions were made respectively.

I wrote about my findings in an article on [medium](https://medium.com/@eddy.esu.22/global-reduction-in-infant-mortality-864d1879a217).

---

### [Analyzing IMDB Ratings of Movies across 100 years for different Work personalities](https://github.com/EdidiongEsu/Movie-Insights)
![](https://github.com/EdidiongEsu/Movie-Insights/blob/master/Pictures/Duration.jpeg)

In this project, I analyzed movies across a century to determine if [IMDB](https://en.wikipedia.org/wiki/IMDb) is a reliable platform to use when checking for ratings of movies. The insights were used to advise on the criterias to have in mind when selecting a movie to watch from a collection. It also looked into picking the best genres depending on what work schedules an individual has.

I wrote about my findings in an article on [medium](https://medium.com/@eddy.esu.22/deliberations-of-a-movie-buff-tips-to-aid-choosing-your-next-cinematic-experience-2fb001372be8).

---
## My Writing

![](https://github.com/EdidiongEsu/portfolio/blob/master/img/medium.PNG)
I write because i love to tell stories. For most projects, I make it a priority to put my findings in writing hoping to inspire or teach someone. I am an author for [Towards Data Science](https://towardsdatascience.com), the biggest data science publication in the world hosted on Medium. [Here](https://towardsdatascience.com/@eddy.esu.22) is my profile. Check [here](https://medium.com/@eddy.esu.22) to read more of my articles with great data insights.

---
## Mini-Projects
* Email classification using Naive-Bayes on [Jupyter Notebook](https://github.com/EdidiongEsu/machine_learning/blob/master/Email%20classifier%20with%20Naive%20bayes/Email%20classifier%20with%20Naive%20Bayes.ipynb).


### Happy Coding!

