# Feature-Analysis
Example feature analysis scripts. These scripts have two poritions. 

First is creating metadata for features based on standardized features names. These names are translated from a compact appreviation based system into the more complex but human form. This will involve translating some abbreviations, numeric etc. for all columns. This will also involve joining external metadata information for vendor information which currently uses a numeric enumeration for its naming convention. This also classifies if this feature should be o, max or mean replaced for null imputation.

The second scripts will grab the feature files from a series of models in a standard location to determine where each feature is used and how often. This is done for both presence as well as some analysis looking at feature importance. This is to be connected to a Tableau workbook which displays this. 
