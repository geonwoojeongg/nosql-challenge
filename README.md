# nosql-challenge

#Background
## The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

#Setup
Firstly, the setup of Pymongo has been done as shown below in the screenshot:
<img width="1121" alt="Screenshot 2023-02-01 at 1 50 59 PM" src="https://user-images.githubusercontent.com/115575880/216135955-8394004e-2bd2-48d7-a55b-b24ec676bb34.png">
Next, a new document has been added to show that I can access the documents, add new data for manipulation and analysis. 

#Analysis
On the analysis file, one of the main tasks of importing a json file with mongodb and then bringing it to a Python environment is to access it with Pandas to make dataframes for much easier visualization and analysis. Mongo data (json) is brought into a Pandas dataframe as shown below: 
<img width="1106" alt="Screenshot 2023-02-01 at 1 54 47 PM" src="https://user-images.githubusercontent.com/115575880/216136863-c36150ee-6de6-44a9-811a-379396244654.png">

Additionally, further detailed search is accessible through Pymongo, such that data with certain values can be gathered (query), sorted by a value in ascending/descending order (sort), and have it to show the first few searches for brevity, as shown below. This can also be made into a new dataframe: 
<img width="1122" alt="Screenshot 2023-02-01 at 1 55 51 PM" src="https://user-images.githubusercontent.com/115575880/216137459-bebfa824-ec20-4a6e-9537-1b742d276ff1.png">

Lastly, even further analysis can be made by formulating an aggregation pipeline, which enables one to show only data with matching values as well as group by a chosen value:
<img width="1115" alt="Screenshot 2023-02-01 at 1 59 00 PM" src="https://user-images.githubusercontent.com/115575880/216138202-ca3baab1-2167-449a-b852-d15ad837362c.png">
