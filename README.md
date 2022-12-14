# Machine-Learning-Project
Cinema Tickets

# About Dataset
Cinema industry is not excluded of getting advantage of predictive modeling. Like other industry e.g. retail , banking and restaurants , sale forecast
can help cinemas for cost reduction and better ROI. By forecasting sale, screening in different location could be optimized as well as effective market targeting and pricing.

Also historical data of sale and movies details e.g. cost, cast and crews, and other project details like schedule, could help producers to select high performance cast and crews and planning for better projects ROI . Also it helps to assign screening location on hot spots and areas.

#  1.Introduction
Sale history of movies in cinemas. The granularity is show time. It means the total sales computed by date, cinema, movie, show time. Also occupation percent (on available cinema capacity) computed at show time. Some tickets might cancelled due to reservation or any other reasons.

# 2.Methodology
### Data Cleaning and Pre-processing:-
The datasets which were collected from Cinema Tickets Dataset from
Kaggle website contain unfiltered data which must be filtered before the final
data set can be used to do analysis. Also, data has some categorical variables
which must be modified into numerical values for which we used Panda’s
library of Python. In data cleaning step, first we checked whether there are any
missing or junk values in the dataset for which we used the is null () function.

### Implementation Steps:-
As we already discussed in the methodology section about some
of the implementation details. So, the language used in this project is Python
programming. We’re running python code in anaconda navigator’s Jupyter
notebook. Jupyter notebook is much faster than Python IDE tools like PyCharm
or Visual studio for implementing ML algorithms. The advantage of Jupyter
notebook is that while writing code, it’s really helpful for Data visualization and
plotting some graphs like histogram and heatmap of correlated matrices. Let’s
revise implementation steps: a) Dataset collection. b) Importing Libraries:
NumPy, Pandas, Matplotlib,Seaborn and sklearn libraries were used. c)
Exploratory data analysis: For getting more insights about data. d) Data
cleaning and pre-processing: Checked for null and junk values using isnull() and
isna().sum() functions of python. In Pre-processing phase, we did feature
engineering on our dataset. As we converted categorical variables into
numerical variables using function of Pandas library. All our datasets contains
some categorical variables.
