# Banglore-House-Prdiction-

Overview OF data:
Feature:

1.Area_type(categorical):
Builtup type,super builtup type ...

2.Availability(categorica):.
available for buying or not.

3.Location(categorical).

4.Size(no of bedrooms) numeric.

5.bath(no of bathrooms)numeric.

6.balcony(available or not)categorical.

7.Price(Numeric).

Data Preprocessing:

Removed Null values.
For categorical features converted them to onehot vectors.
For Size converted string int mixed data to numeric feture.
Engineered a Feature price/sqft.
In some area 2bhk was higher priced than 3bhk so removed  them.

#model:

created a pipeline of svr,linear Regression,lasso regression
and finally got a score of 81%.
