# Education-Inequality
This project aims to tackle the issue of unequal access to education in American high schools by concentrating on the typical performance of students in the ACT or SAT examinations, which are crucial components of college admission requirements. We ask the question does socioeconomic factors impact student testing scores? The primary source of information utilized is the EdGap data set, sourced from [EdGap.org](https://www.edgap.org/#5/37.875/-96.987), which features data from 2016 encompassing the average ACT or SAT scores of schools, along with various socio-economic indicators of the school district. The secondary data set consists of fundamental details regarding each school, acquired from the [National Center for Education Statistics](https://nces.ed.gov/ccd/pubschuniv.asp). It can be accessed here: https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0.

This project was done using the Python language.

To begin the data analysis, I imported the necessary libraries and loaded the data. After that, I inspected the contents of each data set and converted the data types of columns to the correct types. Then, I selected relevant subsets of the data and renamed the columns. To combine the data sets, I joined the EdGap and school information data frames while keeping relevant columns. To ensure data quality, I identified missing values in the data sets. I crafted a train test split for further analysis and did data imputation to handle missing values.
My preparation is titled: SF_Education_Inequality_Data_Preparation.ipynb

The file that communicates my analysis is titled: SF -  Analysis Education Inequality

Communcation Slides will be posted SOON.

In conclusion, our project provides conclusive evidence of a robust relationship between ACT/SAT scores and socioeconomic factors. This is evident from the high accuracy (R2) of our predictions, the statistically significant coefficients associated with these factors, and the measure of accuracy expressed in ACT units. These findings highlight the crucial role of socioeconomic factors in shaping test scores and emphasize the significance of addressing educational inequality through targeted interventions.

Author: Sammuel (Sam) Farias. Seattle University. License: This work is licensed under the Creative Commons CC0 1.0 Universal Public Domain Dedication.
