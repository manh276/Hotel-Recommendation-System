# Hotel-Recommendation-System
create a Hotel Recommendation System by content-based 

CRAWLS:
Data were collected from Booking.vn
RAW Data: CRAWLS-2.csv
Processed Data: df.pkl (pickle file)

MODEL:
CAP2.ipynb is file which preprocessing words and try the model 
Model is called content-based (based on descriptions of hotels) 
  STEP 1. Preprocessing data ( process stopwords, specific characters)
  STEP 2. Measure the similarty beetween hotels by cosine similarty method (Using modules Linear kernel,tFidVectorizer)
  
DEMO APP:
APP.py is file which contains model and create a streamlit app (using folium to show the map)
