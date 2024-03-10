This Project builds a Prophet Machine learning model in order to forecast the price of Tesla 30 days into the future. Project is done in Jupyter Notebook and language used is Python. I have taken Data from 9 March 2023 to 9 March 2024.
I have visualized the historical performance of Tesla through graphs and charts using Plotly express and evaluated the performance of the model against 
real data using Google Finance in Google Sheets. 

Let's start with Importing all necessary libraries, pandas, plotly, prophet. Also initialize plotly.

Read TSLA.csv using pandas and make a DataFrame 

![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/b60ed201-f4aa-474b-8809-05130c79f879)


Check its characteristics

![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/8acecf63-0dd7-4df6-bfaa-c03eedc9b93d)

Visualize Historical Data of Tesla 

![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/6447e2fa-2a6d-4718-b202-77a77a3a0f41)


![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/006fd1f1-9e5c-4331-8f8d-3ca68bc1c3c9)

![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/2f992e48-1cd5-40ee-bd8b-1b2eae49b41d)

![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/f3b20f53-09c9-4f4a-ac3b-70941efb4f51)

DATA PREPARATION:

We only need Date and Close Table so make DataFrame with these two columns. Prophet only accepts ds and y so change Date and Close column names respectively. 

![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/94f54d3d-8c42-455f-bb36-482533fd6d3d)

CREATE Prophet MODEL and then FORECAST

![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/ff1cc5a7-9034-4328-b348-80f215dfa306)

PLOT FORECAST DATA NOW

![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/314e0ffb-c009-4aba-8948-10269d4f10a6)

![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/e2aa023f-6931-4614-af92-9bf2b19c9b57)


![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/611a8782-aedf-4341-bad9-64bdae06e208)

DOWNLOAD DATA USING .to_csv() 

USE GOOGLE SHEETS FOR FINAL EVALUATION (use =GOOGLEFINANCE function to import data of TESLA). 
Add downloaded forecast csv and add prediction column yhat to google sheet.

VISUALIZE THE PREDICTION

![image](https://github.com/Hudabasit/-FORECASTING-Stock-Price-Prediction-of-TESLA-2024/assets/134541252/e664189e-3832-4f7f-bc79-b293cbbad24d)







