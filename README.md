# Forecasting Rainfall Ghana
## 🌧️ Can we forecast rainfall based on Ghanaian farmers’ indigenous weather wisdom?

### Background
Across Ghana’s Pra River Basin, local farmers have long relied on generations of knowledge- using the moon, wind patterns, bird and plant behavior, and even the stars - to anticipate rainfall. With limited access to modern meteorological tools and the inaccuracy of these modern methods in rural Ghana, indigenous knowledge has remained a vital component of agricultural planning and rural resilience.

Despite its importance, this form of forecasting has rarely been digitized, quantified, or evaluated systematically. Thanks to an innovative data collection initiative using the SIW Mobile App, for the first time we have structured data that captures forecasts based on indigenous knowledge alongside actual rain measurements. This opens a new frontier: merging traditional knowledge with AI modelling to build more inclusive and locally-grounded weather prediction models.

In this Zindi challenge I build a classification model that predicts the type of rainfall—heavy, moderate, or small—expected in the next 12 to 24 hours, based solely on indigenous ecological indicators submitted by trained farmers.

The training dataset contains farmers' forecast submissions, the indicators they used (like sun, cloud, wind, moon), and the actual measured rainfall (via rain gauges).

This challenge encourages allows us to explore the scientific potential of Indigenous Ecological Indicators (IEIs), while contributing to an effort that empowers local communities and enriches global meteorological understanding.

This challenge supports the development of accurate, hyper-local weather predictions where traditional models often fail and most importantly validates indigenous methods that helps bridge scientific and cultural knowledge systems, giving agency back to rural communities.

This challenge was sponsored by the Responsible Artificial Intelligence (AI) Lab (RAIL) and the French Embassy in Ghana.
<img width="687" height="360" alt="image" src="https://github.com/user-attachments/assets/f7330232-93c4-4ce2-a181-a5f4d7004744" />

### Data

Key steps in data collection included:
* Rain Gauge Deployment: Calibrated garden rain gauges were installed on the properties of 25 local farmers across three regions (Central, Eastern, and Ashanti).
* Farmer Training: Farmers were trained to record daily rainfall observations and to submit their indigenous weather and climate forecasts using the Smart Indigenous Weather App.
* Use of Indigenous Ecological Indicators (IEIs): Farmers made forecasts based on traditional signs such as cloud formations, sun position, wind, moon, heat, and specific tree or animal behaviors.

The following variables were and continue to be collected are:
* Daily rainfall amounts (measured using the rain gauges.
* Forecast type (e.g., prediction of heavy, medium, small, or no rainfall)
* Ecological indicators used (e.g., cloud, sun, moon, heat, wind)
* Prediction time frame (12-hour and 24-hour forecasts)
* Accuracy of prediction (hit/miss rate, compared with actual rainfall)

The objective of this challenge is to predict the type of rain to be expected in the next 12 to 24 hours.

### Evaluation
The evaluation metric for this challenge is F1 Score.

