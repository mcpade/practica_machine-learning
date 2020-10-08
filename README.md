# Práctica: Módulo Machine Learning 101 - Bootcamp KeepCoding - BIG DATA & MACHINE LEARNING

# Machine Learning

In this practice, different Machine Learning algorithms are used and compared to be able to predict the price of Airbnb homes. The code is developed in Python

Concepts covered in this practice:

- Python **numpy**, **pandas** and **Sklearn** libraries
- Division of data in train and test
- Cleaning and data processing
- Generation of new features
- Exploratory analysis of numerical variables. Statistical data, distributions
- Treatment of outliers
- Exploratory analysis of categorical variables
- Exploratory analysis of Boolean variables
- Coding of categorical variables
- Correlation analysis
- Standardization and normalization
- Models: Use and comparison
      - Linear regression
      - Ridge regression
      - Feature selection: Lasso
      - Regression tree
      - Random forest
      - Boosted trees
      - SVR
     

## Statement

The objective of the practice is to tackle a realistic Machine Learning problem following the methodology and good practices explained during the theoretical classes.

**Regression problem: Predict airbnb price using available data**

It will be valued:

• Generation of new features from existing ones

• Coding of variables

• Exploratory analysis

• Selection and evaluation of the model

• Comparison of different algorithms


## Data set

The chosen data set is [éste](https://public.opendatasoft.com/explore/dataset/airbnb-listings/export/?disjunctive.host_verifications&disjunctive.amenities&disjunctive.features&q=Madrid&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQ09VTlQiLCJ5QXhpcyI6Imhvc3RfbGlzdGluZ3NfY291bnQiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20ifV0sInhBeGlzIjoiY2l0eSIsIm1heHBvaW50cyI6IiIsInRpbWVzY2FsZSI6IiIsInNvcnQiOiIiLCJzZXJpZXNCcmVha2Rvd24iOiJyb29tX3R5cGUiLCJjb25maWciOnsiZGF0YXNldCI6ImFpcmJuYi1saXN0aW5ncyIsIm9wdGlvbnMiOnsiZGlzanVuY3RpdmUuaG9zdF92ZXJpZmljYXRpb25zIjp0cnVlLCJkaXNqdW5jdGl2ZS5hbWVuaXRpZXMiOnRydWUsImRpc2p1bmN0aXZlLmZlYXR1cmVzIjp0cnVlfX19XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZX0%3D&location=16,41.38377,2.15774&basemap=jawg.streets), extracted from Airbnb using scraping techniques. Among the options, I recommend using extract (“Only the 14780 selected records”), since it minimizes execution time and avoids memory problems on computers with fewer features.

The csv file that is obtained at the time of the practice is in the **data** folder of this repository
