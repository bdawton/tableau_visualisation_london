
# Tableau London General Election Visualisation

The goal of this project is to create a [Tableau visualisation of London](https://public.tableau.com/shared/4HJPKQ94X?:display_count=n&:origin=viz_share_link) to determine whether the voting patterns of each of the city's 23 Boroughs can be predicted based on features such as salary, population size ... and how diligently they recycle!

Initial data is taken from:
- https://www.kaggle.com/datasets/justinas/housing-in-london
- https://data.london.gov.uk/dataset/statistical-gis-boundary-files-london
- https://commonslibrary.parliament.uk/research-briefings/cbp-8647/
- You will also need the included *constituencies_boroughs.csv* file created by yours truly!

Flow:
1. Raw data is first analysed and processed in *london.ipynb*, before being exported as corresponding spatial files (*LondonFiles.cpg, .dbf, .prj, .shp, .shx*; the *.shp* file is too big for GitHub, and is in the *.zip* file, so uncompress it if you want to use it!).

2. Processed data is then visualised in Tableau ([click here to view](https://public.tableau.com/shared/4HJPKQ94X?:display_count=n&:origin=viz_share_link).

History:
- *v.0.1:* initial attempt at visualisation for a set of features each election year, and comparing impact of Brexit on voting habits by comparing predicted 2019 results to actual 2019 results. (Not that different in London, model still needs fine-tuning though!)

