# machine_learning_data_preparation
Document approaches and methods for processing and transforming data to meet machine learning requirements

### csv_fillna1.ipynb
Use pandas methods to fill NA's for different type of data and circumstances. Different filling methods are discussed, such as fillna(0), fillna(method="ffill"), fillna(method="bfill"), interpolate(), and interpolate(method='time'). 
In addition, dropna() can be potentially used, especially for items (rows) having majority or all values missing, in this sample data set , row of "1/17/19" with all of its values being missing, could be potentially removed by using dropnd() method: df.dropna(how ="all").

