# DS-6306_Case_Study_01
Welcome to the project page for SMU DS-6306 Case Study 01. 

For this case study, we investigated two datasets; a Beers dataset contained information for 2,410 craft beers while the Breweries dataset contained information for 558 breweries.

Through the analysis, we found that there were several states with few breweries present where the creation of a new facility could potentially create more income. In addition, we analyzed the correlation between IBU and ABV and found that as IBU increased, so too did ABV, inferring that as bitterness increases so too does alcohol content.

We also investigated the median IBU and ABV per state, which was remarkably close to the mean, indicating that the distribution was symmetrical. We explored the trends of IBU and ABV between IPAs and Ales and found that we could discern the two types of beers with an accuracy of 88% based on IBU and ABV units when using KNN as the classifier, where k=5 produced the highest accuracy. However, since Budweiser trends towards lager-style beers, we thought it would be best to focus our analysis on where Budweiser could build a facility, or purchase an existing facility, in a region that preferred lower IBU and ABV beers.

In order to find the best possible target state, we investigated the types of beers that are most popular per state. We found that cider was underrepresented in most states, with exceptions for Michigan and Oregon. Next, we looked at lager and pilsner-type beers per state and found that there were no facilities for these types of beers in several Southeastern states. We also looked at the correlation between ABV and serving size and found that there was a preference for 4-8 oz servings with alcohol content between 4-7% in the Southeastern US.


The project hierarchy is outlined below. 
```{bash}
.
|-- Figures
|   |-- Breweries per State.png
|   |-- Median IBUs per State
|   `-- Median IBUs per State.png
|-- LICENSE
|-- README.md
|-- datasets
|   |-- Beers.csv
|   `-- Breweries.csv
|-- instructions
|   |-- case_study_01.txt
|   `-- case_study_01_rubric.txt
|-- presentation
|   `-- old
|       |-- Very Beer Focused PPT_case_study_01_presentation.pptx
|       `-- case_study_01_presentation.pptx
`-- rmarkdown
    |-- case_study_01_final.html
    |-- case_study_01_final.rmd
    `-- old
        |-- case_study_01.html
        |-- case_study_01.rmd
        |-- week_8_case_study_01.html
        `-- week_8_case_study_01.rmd

7 directories, 17 files
```    

