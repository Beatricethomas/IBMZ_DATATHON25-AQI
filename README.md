# IBMZ-DATATHON25--AQI
## TEAM : DataXplorers
## TEAM NO : SAV033
### AQI prediction and comparison in metropolitan cities.

## Problem Statement :

Air pollution has become a critical health and environmental issue in major urban cities like Bangalore, Chennai, Delhi, and Mumbai. High levels of Air Quality Index (AQI) can cause respiratory problems, cardiovascular diseases, and reduce overall quality of life. Despite the availability of historical AQI data, real-time or short-term forecasts are often inaccessible or inaccurate, making it challenging for residents to plan outdoor activities or take necessary precautions.

Traditional AQI forecasting relies on complex machine learning models or sensors, which may not always be feasible for smaller organizations or public awareness platforms. Additionally, most existing systems provide forecasts by dates, which can be less intuitive for users who prefer day-wise guidance (like Monday, Tuesday, etc.) for planning their week.

## Datasets Used

The system uses a historical AQI dataset spanning 24 years, containing information for multiple cities such as Bangalore, Chennai, Delhi, and Mumbai. 
The dataset includes:

AQI values (target variable)

Environmental and pollution-related factors: PM2.5, PM10, NO2, CO, O3, SO2

These datasets allow the system to understand both natural and human-induced factors affecting air quality.

## Proposed ML Model & Methodology

The forecasting approach is lightweight and data-driven, not relying on complex models. Instead of heavy machine learning models, the system uses a historical trend-based method:
The last 7 days average AQI is used as a base value for prediction.
Small daily variations (±1%) are applied to simulate realistic fluctuations.
City-specific adjustments (e.g., reducing Chennai’s values) ensure predictions are realistic.
Although no advanced ML model is used, the system calculates evaluation metrics such as R² Score, MAE, RMSE, Accuracy, Precision, Recall, and F1 Score to validate performance. This method is interpretable, robust, and easy to update with new data.

## Features Used
Pollution indicators: PM2.5, PM10, NO2, CO, O3, SO2

City encoding: Each city is encoded numerically for model processing.

## Linuxone deployment : 

![WhatsApp Image 2025-10-12 at 11 48 17_f30f1a5d](https://github.com/user-attachments/assets/1d1a9709-fea7-4772-bee0-b4cd5e66ed90)

<img width="994" height="936" alt="Screenshot 2025-10-12 114902" src="https://github.com/user-attachments/assets/26c65a3d-7daf-494a-bf68-ba3cacb4763c" />

![WhatsApp Image 2025-10-12 at 11 49 52_3639397b](https://github.com/user-attachments/assets/f14424e5-ea44-4a11-b005-e4b04f215c04)

![WhatsApp Image 2025-10-12 at 11 49 53_b0abacf0](https://github.com/user-attachments/assets/a3362794-69a4-4dba-8149-8bb14af52bcf)


