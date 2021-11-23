This project aims to ascertain the key cost drivers in freight logistics by generating predictions for future freight prices. To select a prediction method, the regression models were explored and compared. As predicting the cost is of a regression task, the MAE metric was chosen to compare baseline and machine learning model.
Consequently, to efficiently handle the freight-cost dataset of EGIM company, this paper explores some data analysis to extract the most important features. Ensemble based regression model is used to perform the task. 

The goal of this project is to create an optimized pricing model, that provides provide lowering cost to carriers and shippers, hence to;
• Determine the key cost drivers from the data
• To pursue a unique and clear objective to cut cost
• Identify segments where we can lower the rates and as well as highlight segments where it is underpriced.


This dataset provides the export/import shipment and pricing from 2017 to 2019. The dataset is obtained from EGIM database, which contains
details of shipment transactions that have taken place in Germany for three years. It has \textit{8751} observations and \textit{21} features.

For each shipment transaction, various information are provided and can be
categorised as follows:
• ID (Transaction ID)
• Date (Dispatch dates, Delivery dates)
• Sending and receiving Railway Stations
• Container classification (Number, Type, Size)
• Shipment direction (Import, Export)
• Carrier capacity (Name, Number, Gross Weight, TEU volume)
• Shippers information (Name, Postcode, City name, etc)
• Transaction price (Charged in €)

The newly developed insight on the key cost drivers in freight logistics should be helpful to manage the implementation of the computational segment. This knowledge is general enough to be readily adapted for different shippers and carriers. Although, the logistics cost categories may remain the same, the elements of each category can vary from case to case. In this project, the regression based machine learning model was built to understand the variance of data with respect to cost. Based on the feature importance, key cost drivers were extracted and these cost drivers can be used in day to day business to control the cost of the freight logistics.
