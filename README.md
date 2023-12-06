# Breast Cancer Survival Analysis

## 1. data wrangling

- drop all missing values and Patient_ID column
- add a column, compute the time since surgery to last visit
- convert all String columns to numeric values

> Xinyu: 
>
> I have converted all the strings into numeric values for ease in the final predictive analytics. 
>
> The processed dataset is named `dataset`. 
>
> If you wish to use the original strings for data visualization, please utilize the variable `data` (this dataset has all missing values removed and an additional column: '*Days Between Surgery And Last_Visit*', added).
>
> 我把所有字符串全部转换成numeric了，方便最后predictive analytics，处理后的数据集命名为dataset。你们进行data visualization时如果想用到原始字符串的话，可以用变量data(这是去除掉所有缺失值并增加了一列'Days Between Surgery And Last_Visit'的数据集)。

## 2. data visualizations

- Heatmap, Histogram, Pie chart, Scatter plot, Box plot, Bar chart, Table, Stacked bar chart



### discussion

Box plot:

- The age distribution differences among different types of breast cancer are displayed in the box plot. Upon observing the average ages of patients with three types of breast cancer, it is noted that patients diagnosed with 'Infiltrating Lobular Carcinoma' have the lowest average age, while those diagnosed with 'Infiltrating Ductal Carcinoma' have the highest average age. However, the average ages for the three histology types range between 50 and 60 years, showing little variation. Additionally, by examining the interquartile range in the box plot, it can be observed that the onset age for 'Mucinous Carcinoma' tends to be more concentrated compared to the other two types.

Scatter plot:

- The image comprises 12 scatter plots and 4 histograms. From the scatter plots, we can observe the relationships between different features. For instance, there exists a positive correlation between Protein1 and Protein2, whereas a negative correlation is observed between Protein3 and Protein4. Additionally, it seems that there is no apparent relationship between Patient_Status and Protein1, Protein2, Protein3, and Protein4.



## 3. Predictive Analytics

- SVM
- Logistic Regression
- Random Forest
- SMOTE

