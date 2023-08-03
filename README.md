# Inside Airbnb

The project aims to assist users in making informed decisions for their Amsterdam stay, providing valuable insights into the city's Airbnb market. 

![image](https://github.com/snehakhirwal02/BI-Project-Inside-Airbnb/assets/111349244/04a9b368-0424-4775-af98-62d576f48682)

**Motivation behind choosing Amsterdam over other cities/countries:**
- One of the most famous tourist attractions in Europe
- Good quantity of data points for analysis and visualization
- Personal Interest in knowing the statistics of the airbnbs in Amsterdam

The workflow pipeline involves:

 **Data exploration** (Excel + Python) --> **Data pre-processing and analysis** (Python) --> **Visualisation** (Power BI)

In this Airbnb project, I developed a comprehensive multi-page dashboard in power BI focused on Airbnb in Amsterdam. Using Python, I explored and cleaned the Airbnb data to ensure accuracy and relevancy. Later the cleaned data is used to make sense out of the data and get valuable insights shown below

![image](https://github.com/snehakhirwal02/BI-Project-Inside-Airbnb/assets/111349244/084a20a0-0498-4114-9299-605197d942c6)

#### Data pre-processing
 
- Deletion of _irrelevant and blank columns_ 
- Removing of _duplicate rows_ with same ids of the listing but different airbnbs
- Changing the _format and datatype_ of price column in listings table
- Removal of rows when the _price is equal to 0_
- _Outlier detection_ and removal on basis of minimum_nights with z-score

#### Dashboard

- The dashboard offers a holistic view of Airbnb accommodations in Amsterdam, with an **overview page** providing the key insights. 
- The **personalized page** allows users to customize their Airbnb selections based on specific preferences.
- The main highlight of the project lies in the **Hidden Gems** dashboard. Here, users can uncover hidden gems - affordable yet outstanding accommodations. I have attached a snapshot of the hidden gem dashboard with the criteria that I have considered to declare a particular airbnb a hidden gem. 

![image](https://github.com/snehakhirwal02/BI-Project-Inside-Airbnb/assets/111349244/710ecbf7-caa5-4bab-bfb5-25c9b39188c4)

Source of data: http://insideairbnb.com/get-the-data/

**Python code used to process the data and the final Power BI dashboard can be found in the file attachments**
