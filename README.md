# Candy-data
Summary :
* I imputed the NaN values, changed the column names, wrong data type and wrong range of values
* I used pd.to_numeric to convert to numbers and the rows that was not able to convert became NaN then float then int
* I created new dataframe for candy to clean it and get useful info, i also made new df to know the most and least popular candy
* state column had too much nuique values so i dropped it
* Using fuzzy_wuzzy to remove mismatch country names
* I created new df for media to know the most popular website
