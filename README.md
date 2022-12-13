# World Happiness (EDA)

[![kaggle](https://img.shields.io/badge/_-Open_in_Kaggle-informational?style=plastic&logo=kaggle&logoColor=white&color=045bab&link=https://www.kaggle.com/code/martinab/world-happiness-plotly-eda)](https://www.kaggle.com/code/martinab/world-happiness-plotly-eda)

### Introduction
The aim of this project was to demonstrate different visualisation techniques by using plotly library and analyse World hapiness datasets (2015-2019).

Before I started exporing and visualising the data, I realised that I was facing a setback - naming conventions of datasets columns are a mismatch. I have sorted this issue out in Data Manipulation section. Of course, I could use different approach to tackle this problem. 

At some point I created additional columns for continent and region by using pycountry_convert library.

<p align="center">
<img height="475em" width="650em" src="https://github.com/Kaggle-Projects-Solutions/World-Happiness-EDA/blob/main/happines%20score.png" align = "center"/>
</p>

I tried to use dynamic graphs and charts in EDA section where possible. It's cool to have fancy visuals, but it's even cooler to be able to provide insight... 📊📈📉
<br><br/>


### Targets
 1. Combine all available datasets together by using pandas concat function.
 2. Data cleaning and manipulations
 3. Data enrichment - add country and region flags/columns by using pycountry_convert library and custom mapping.
 4. Use plotly to create interactive visuals.
 5. Provide insight based on data and data visualisations.

### Acknowledgements

The source of data for this project is from Kaggle's dataset called World Happiness Report. Data can be also obtained on the World Happiness Report website. <br><br/>

Useful links:
- [World Happiness Report | Data Repository](https://worldhappiness.report/archive/)

