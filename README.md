# Creating Alternative Stock Indexes Using Unsupervised Machine Learning
Use unsupervised machine learning to create stock indexes that don't take into consideration market capitalization.
  
## Overview of the analysis
- Current indexes methodology are driven by economic representation of the stock market, since they weight the size of each company (market capitalization)
- This methodology makes the index very dependable on very large companies and don’t provide enough risk diversification, especially in emerging countries like Brazil, where the concentration on big names gets even stronger (therefore we are using this country it in this project)
- Investors don’t really care about market capitalization; they are more concerned in having a better return for their risk (better Sharpe Ratio)
- Classic style factors indexes are assumed to have low correlation within themselves, but this assumption is not necessarily true. 
- In this project we will creat alternative indexes that provide a better approach for an investor perspective.
- The Analysis will be elaborated in "PCA on Stock Market" file.
 
- ## Resources
- Data Source: Bloomberg
- Software: Python, Jupyter Notebook, Powerpoint

## Communication Protocols
  Given the data sensitity, this repo will be made private after second segment, with access provided only to instructional staff

## Note on Branches
  As this is a solo project, no brances are necessary
  
## Technology
  All technology aspects will be treated in technology.md file
  
## Database
  Data will intially be extracted from Bloomberg files (bbg format), and transformed into Dataframes

### Schema

- Raw Data

   ![Schema](/Schema.png)


