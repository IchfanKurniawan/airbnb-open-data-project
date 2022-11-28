# Airbnb Open Data Project  
  
## <span id='summary'>Executive Summary  
---  
Source of Dataset: https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata  

<br>  

[**Project notebook is here!**](https://github.com/IchfanKurniawan/airbnb-open-data-project/blob/main/Airbnb-open-data-project.ipynb)  

<br>  

**From the POV of Airbnb room owner**, this project could benefit them to maximize the total charge price of a room. This project reveals that from given dataset & features, these are the strong predictors for total charge price:  
    
`minimum_nights`, `review_rate_number`, `bin_reviews_per_month`, `bin_number_of_reviews`, `log_availability_365` `room_type_Private`  
  
Owner of Airbnb hotel or building could make improvements on those stronger predictors to maximize charge of the total_price (price + service_fee).  
    
    
<br>  
  
**From the POV of Airbnb owner**, this project could enrich their information & knowledge. The Exploratory Data Analysis (EDA) reveals some useful informations such as:
- Most of host located in Manhattan, Broxlyn, and Queens,  
- Most of room type are Entire home/apt and Private room,    
- The range of service fee is 10 - 240 and the range of price is 50-1200, 
- and more you could find them in EDA section.

  
To make a prediction of total price of a room, it is quite difficult if it is only from the information given in the dataset. Therefore I would not continue my project into modeling phase & evaluation phase, because I know that the model
would not perform well with the given features.  
    
For further improvement of model, we could add more additional feature for each sample.  
I proposed we should gather information about:
- characteristic of room (size, bed type, bath tube, bed size, etc)
- building facilities (balcon, wifi, pool, breakfast etc)
- nearby public transportation/ease of access
- nearby city landmark/recreation
- nearby restaurant/supermarket/other public facilities
