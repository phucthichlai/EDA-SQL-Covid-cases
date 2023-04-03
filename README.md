# <h1 align="center"> :space_invader: COVID-19 Pandemic EDA using SQL and Python :space_invader: <img src="https://user-images.githubusercontent.com/104643138/229413864-497b8358-eb53-4b82-9650-a086a1cb4f9a.png" width="50" height="50"></h1>

## **1. Introduction** :pushpin:

- **About COVID-19 Pandemic**: COVID-19 is the disease caused by SARS-CoV-2, the coronavirus that emerged in December 2019.
COVID-19 has caused nearly 7 million deaths (https://www.worldometers.info/coronavirus/) as well as lasting health problems in some who have survived the illness. The coronavirus can be spread from person to person. It is diagnosed with a test.

- **Objective**: This project aims to perform Exploratory Data Analysis with SQL and Python to review the situation in each country, region, income groups,... and generate some insights about the pandemic.

- **Target Audiences**: The findings may provide some meaningful insights for... possibly everyone.

## **2. Methodology**:microscope:

- **Data Source:** ["COVID 19 PANDEMIC"](https://ourworldindata.org/coronavirus#coronavirus-country-profiles) from OurWorldInData.org - a popular website for publishing the “research and data to make progress against the world’s largest problems”.

- **License:** The data is available for download under Creative Commons BY license.

## **3. Findings Summary** :bulb:

- <strong>Total infected cases by countries:</strong>
<img width="1000" alt="Ảnh chụp Màn hình 2023-04-03 lúc 13 20 04" src="https://user-images.githubusercontent.com/104643138/229418126-ec61c53f-9df3-4fd8-9545-69427dd710a4.png">

<img width="1000" alt="Ảnh chụp Màn hình 2023-04-03 lúc 13 16 46" src="https://user-images.githubusercontent.com/104643138/229417603-88470681-b9fd-4fda-a7b3-afc792551ee6.png">

=> Top 3 countries with the most cases are also the <strong>top 3 most populated countries</strong>. Others in top 10, such as Brazil, Germany, Japan, also have a place in top 20 most populated countries.

=> So <strong>why France and Germany, for example, has such a high infection rate?</strong> The answer remains unknown.

=> Apart from India and Brazil, the rest are all <strong>countries with high income</strong>.

=> <strong>China</strong> had a high infection rate because this is the origin of the Pandemic. However, its <strong>percentage of death per total case and per population is comparatively low</strong> in the top 10 rank. For every 100.000 Chinese, there are only 8 Chinese died of Covid, the figure was 37 in the India although they have nearly the same population.

- <strong>Total infected cases by regions/ groups:</strong>
<img width="984" alt="Ảnh chụp Màn hình 2023-04-03 lúc 13 29 39" src="https://user-images.githubusercontent.com/104643138/229419391-4011389d-17aa-4d55-aa74-f541bb74cecd.png">

=> COVID 19 seems to be a pandemic of <strong>the rich</strong> when income has a <strong>negative relationship</strong> with the total number of cases, although the high income countries's population is the least among the 3 groups.

- <strong>Total fatal cases:</strong>
<img width="984" alt="Ảnh chụp Màn hình 2023-04-03 lúc 13 31 12" src="https://user-images.githubusercontent.com/104643138/229419555-889ee1c1-b060-4660-9056-214a2b2796c3.png">

<img width="984" alt="Ảnh chụp Màn hình 2023-04-03 lúc 13 31 44" src="https://user-images.githubusercontent.com/104643138/229419662-a1ea5194-fee1-4732-97e6-ad897da01d92.png">

<p>=> <strong>China</strong> was not in this rank, while <strong>Russia</strong>, though not present in the top 10 highest total cases, ranked the fourth in the list. The rest are familiar countries in the previous table.</p>

- <strong>Total fatal cases by regions/groups:</strong>

<img width="984" alt="Ảnh chụp Màn hình 2023-04-03 lúc 13 34 25" src="https://user-images.githubusercontent.com/104643138/229419966-73541457-489c-4950-8310-77c38fcd308d.png">

<p>=> The COVID-19 pandemic was totally a nightmare for the <strong>rich countries and Europe</strong>. However, while <strong>Africa and Low middle income group</strong> recorded a relatively low number of fatal cases, their <strong>death percentage over total cases</strong> were high. This may reflect the quality of medical and health care competency and political stability of the region in face of the COVID outbreak.</p>

- <strong>The peak of death percentage per total cases in every country in 2023</strong>
<img width="984" alt="Ảnh chụp Màn hình 2023-04-03 lúc 13 39 07" src="https://user-images.githubusercontent.com/104643138/229420603-bfba83a1-1759-4847-856f-667b56ae0ad3.png">

<p>=> Doing a little reserach about Yemen, according to BMJ - an NPO online journal in medical and healthcare - in 2020 (https://www.bmj.com/content/370/bmj.m2997): "Around 18% of the country’s 333 districts already have no doctors, and many of those who remain have been unpaid for nearly two years. MedGlobal said that there were now 10 healthcare workers for every 10 000 people, less than half the World Health Organization benchmark.Yemen recorded its first covid-19 case on 10 April. Official figures put the number of confirmed cases at over 1600, with nearly 500 deaths—a mortality rate of 27%, which is one of the highest in the world and five times the global average."</p>

<p>=> According to Médecins Sans Frontières (MSF) - an international medical humanitarian organisation - in 2023 (https://www.msf.org/yemen-abs-hospital-overwhelmed-medical-needs-surge): “Supporting Abs hospital has become one of MSF’s biggest humanitarian responses worldwide, but today we have reached the limit of our capacity to respond, in terms of space, human resources and supply. The increased demand on Abs hospital’s services is due to a number of factors, including the protracted conflict in Yemen. To make matters worse, the poor living conditions in camps for displaced people in Abs district, including a lack of clean water and sanitation, lead to disease outbreaks. The situation was exacerbated in 2022 when funding cuts caused several health providers to stop working.</p>

<p>=> The situation in top 5 (Sudan, Syria, Somalia) remained the same with ongoing conflicts, wars, and poor living condition.</p>

- <strong>The peak of fatal cases percentage per total cases in every country in 2020</strong>
<img width="984" alt="Ảnh chụp Màn hình 2023-04-03 lúc 13 40 31" src="https://user-images.githubusercontent.com/104643138/229420812-dd433bbe-c74c-4d08-9f00-f62520aaad18.png">

- <strong>The peak of fatal cases percentage per total cases in 2023</strong>
<img width="984" alt="Ảnh chụp Màn hình 2023-04-03 lúc 13 46 02" src="https://user-images.githubusercontent.com/104643138/229421685-7f6c575b-dbfb-473e-98db-05eb7051ca36.png">

- <strong>Peak period of new cases recorded by continents:</strong>
<img width="984" alt="Ảnh chụp Màn hình 2023-04-03 lúc 13 56 14" src="https://user-images.githubusercontent.com/104643138/229423422-6965dfbb-8094-4a46-b846-36cec7fb46ec.png">

<img width="984" alt="Ảnh chụp Màn hình 2023-04-03 lúc 14 02 52" src="https://user-images.githubusercontent.com/104643138/229424222-ab1b15dd-b778-47a3-9110-e98551de5b41.png">

=> While Europe, America, and Oceania witnessed the pandemic peak at relatively the same period, <strong>Africa and Asia</strong> recorded the peaks quite differently. Let's go into detail.


## 4. Technologies used ⚙️:satellite:
- [Python](https://coursera.org/share/9633cd154ac74544f87f83434258a90b) <img src="https://github.com/PrinceCorwin/Useful-tech-icons/blob/main/images/python.png" width="24" height="24">
- [JSON](https://www.json.org/json-en.html) <img src="https://user-images.githubusercontent.com/104643138/229423990-96f48b5e-0236-4948-bfaf-96b62c02824e.png" width="24" height="24">
- [Jupyter Notebook](https://jupyter.org/) <img src="https://user-images.githubusercontent.com/104643138/226098051-177ede6d-3fe5-49a8-8f57-446caf49f94c.png" width="24" height="24">
- Python Libraries: [Pandas](https://pandas.pydata.org/) <img src="https://user-images.githubusercontent.com/104643138/225993416-31cf4034-962c-4842-8821-5a5ccfc8e729.png" width="24" height="24"/> | [NumPy](https://numpy.org/) <img src="https://user-images.githubusercontent.com/104643138/225993758-e1b3af8b-47a0-405d-90ff-b2edeeac3d37.png" width="24" height="24"/> | [Matplotlib](https://matplotlib.org/) <img src="https://user-images.githubusercontent.com/104643138/225994026-078da32e-a169-4f83-9fa4-fc0d00c911c1.png" width="24" height="24"/>
| [Folium](https://pypi.org/project/folium/) <img src="https://user-images.githubusercontent.com/104643138/229423621-7d7a5803-1962-47b6-8d28-1c6900294bce.png" width="72" height="24"/> | [Plotly](https://plotly.com) <img src="https://user-images.githubusercontent.com/104643138/226207356-729c069e-8a89-442d-99d4-cecb345fbbcc.png" width="24" height="24"/>

## You can reach me at 👇
<img href="https://www.facebook.com/dobaophuc98/" src="https://img.shields.io/badge/Facebook-@dobaophuc98-1877F2?style=for-the-badge&logo=Facebook"/>
<img href="https://www.linkedin.com/in/andy-data-analyst/" src="https://img.shields.io/badge/LinkedIn-@Andy_data_analyst-0A66C2?style=for-the-badge&logo=LinkedIn"/>

<img src="https://img.shields.io/badge/Gmail-dobaophuc1998@gmail.com-EA4335?style=for-the-badge&logo=Gmail"/>
