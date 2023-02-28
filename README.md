#    EXPLORATORY DATA ANALYSIS ON DIANMOND PRICE:
##      1. IMPORTING THE REQUIRED LIBRARIES:
   ![image](https://user-images.githubusercontent.com/46246463/221762103-aa8778b4-0922-4145-88e2-0fb5eec7bbaa.png)

##      2. PRE-EDA CHECK ON THE DATASET NATURE:
   ###          a. GETTING THE COLUMN CHARACTERISTICS:
   ![image](https://user-images.githubusercontent.com/46246463/221762146-8f58c561-050c-49f5-802e-ad389e45e544.png)

   ###           b. DROPPING DUPLICATE COLUMNS: HERE ‘Unnamed: 0’
   ###           c. STATISTICAL CHARACTERISTICS OF THE DATASET:
   ![image](https://user-images.githubusercontent.com/46246463/221762236-4d85ad32-654f-4dfa-9b7c-a978e9efb999.png)

##      3. UNIVARIATE ANALYSIS
   ###           a. CHECKING FOR OUTLIERS USING BOXPLOTS:
   ![image](https://user-images.githubusercontent.com/46246463/221762613-af25e411-1a72-4c06-ba73-7a566d8a359b.png)

   ###           b. Getting rid of outliers from all the columns to reduce the lack of
             consistency of our data as some of the outliers have very high extreme
             values and could cause improper analysis.
   ![image](https://user-images.githubusercontent.com/46246463/221762667-b987a8b8-f103-4496-9a87-583a202e7e7f.png) ![image](https://user-images.githubusercontent.com/46246463/221762684-2ebe9b3e-2a60-48f3-a8fb-ea30e7a9825b.png)


   ###          c. VISUALIZING THE DIAMOND PROPERTIES USING BAR GRAPH AND KDE PLOT
   ###          d. CHECKING FOR SKEWNESS OF THE ATTRIBUTES OF THE DIAMONDS:
   ![image](https://user-images.githubusercontent.com/46246463/221762740-55fbb5c4-0dca-4395-8dbd-96483db13ca1.png)

##      4. MULTIVARIATE ANALYSIS:
   ###           a. PLOTTING CORRELATION AMONG THE ATTRIBUTES USING HEAT MAP:
   ![image](https://user-images.githubusercontent.com/46246463/221762762-432c63f7-04cd-4e5e-8868-21cebf09f6d9.png)

   ###           b. PLOTTING CORRELATION OF DIAMOND PRICE WITH CARATS USING JOINTPLOT
   ![image](https://user-images.githubusercontent.com/46246463/221762779-4258c1d8-bb57-41b4-80f9-11182d3cb936.png)

##      5. CATPLOT VISUALIZATION FOR CLARITY, CUT AND COLOR OF THE DIAMONDS:
   ![image](https://user-images.githubusercontent.com/46246463/221762898-589d56a6-6793-452a-983f-c59a3946b2ac.png)
