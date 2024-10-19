# __Database Analytics(using ETL,EDA)__

The integration and analysis of three related
datasets about books that are sold in bookstores is the main
aim of this project analysis. The two structured CSV datasets
and one semi-structured JSON dataset were carefully selected
to allow for the logical connections.<br> Extract, Transform, Load
(ETL) process was performed, that is the process of integrating
the datasets into MongoDB programmatically using Python in
the Jupyter Notebook environment was done. <br>Then, in this
analysis Exploratory Data Analysis (EDA) was carried out, which
involved thorough analysis, pre-processing, and visualization.<br> A
range of visuals, like graphs and histograms, were utilized to
study and evaluate the variables like book availability by genre
and total and individual count of books according to their
category.<br> And then finally after the processing of data and
adding insights from the EDA, the data was programmatically
stored in PostgreSQL respectively.<br> Therefore, the project's
methodology and goals are summarized in this abstract in
detail, which also covers the important phases of dataset
integration, __ETL, EDA,__ and storage.

## __Introduction To Project__ <br>
In this project, we have aimed to find three related datasets
that could be connected logically. Basically, we searched for
two csv datasets and one JSON dataset. The datasets we have
used in this project are of books that are available in a
bookstore.<br>
In this project we have considered two csv files i.e. two
structured datasets and one JSON which is a semi-structured
dataset respectively. <br> The selected datasets have been initially
stored in MongoDB programmatically, by using python in
Jupyter Notebook, before performing operations on it. <br>  We can
say that this was the ETL process. Then thereafter, the EDA
process, i.e. the Exploratory Data Analysis was performed on
the datasets; wherein, the data was analysed, pre-processed,
and visualized thoroughly. <br> In this EDA process various
visualizations are being plotted like for example a bar graph,
histogram, etc. were plotted to check various aspects of the
datasets like for example, checking the availability of a book of
a particular category, checking the overall and also the
individual count of the books available in the store based in
their genre, etc. <br> Then finally all the processed data we got as
an output has been stored in PostgreSQL programmatically
respectively.

### __FlowChart__
<img width="197" alt="image" src="https://github.com/user-attachments/assets/5fa7f2fa-d9a6-4730-ae83-55ef008ffc7a">

#### __Conclusion__<br>
To conclude the proposed analysis, a systematic process was
followed in the methodology used to assess all the three
datasets (two CSV files and one JSON file) respectively. The
datasets made it easier to access specific book details. Using
Python in the Jupyter Notebook environment and libraries like
pandas, numpy, and matplotlib.pyplot, the dataset was first
loaded into MongoDB. The dataset was then subjected to the
ETL procedure (Extract, Transform, Load), which included file
merging, transformation of pandas, retrieval of data from
MongoDB, and finally descriptive analysis.
The methodology's next step was Exploratory Data Analysis
(EDA), which was performed after the ETL process which tried
to improve the quality of data by removing errors and
unwanted information. Following analysis, the data was
transferred to a PostgreSQL Database Management System
(DBMS) via a connection using the required library. The
connections were committed and closed, and the data was
exported to PostgreSQL finally.
The data was extracted successfully from PostgreSQL and then
transformed into a variety of visualizations using the required
Python libraries, including Histograms, Boxplots, Scatterplots,
Correlation matrices, and Heatmaps. This thorough process
made sure that the datasets were evaluated in an organized
and perfect manner respectively
