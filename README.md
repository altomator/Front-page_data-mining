# Newspaper front page faces data mining

This work is a compagnon project of the [GallicaPix PoC](https://gallicapix.bnf.fr/). It leverages a dataset of heritage French periodicals  built under the [GallicaPix](https://github.com/altomator/Image_Retrieval) scope.


## Face detection pipeline
Various face detection tools have been applied to the front page illustrations of the [Excelsior](https://gallica.bnf.fr/ark:/12148/cb32771891w/date) newspaper (1910-1943): IBM Watson Visual Recognition, Google Cloud Vision, OpenCV/dnn. See this [github](https://github.com/altomator/Image_Retrieval). Gender can be infered by some of the tools. 

![Faces](https://github.com/altomator/Front-page_data-mining/blob/main/images/faces.jpg)

Both the detected faces and the genders have been manually corrected on the page samples used for the quantitative analysis.


## Analysis
The following charts make use of the quantity of faces detected and show the evolution of the Excelsior editorial choices regarding human faces on the front pages, from 1910 to 1920. The categories analysed are :

- men group (from 1 to x men)
- women group (from 1 to x women)
- mixed group (from 1 to x persons)
- couple (one man and one woman)


![Means of transport vs other ads, per year](http://www.euklides.fr/blog/altomator/Image_Retrieval/Ads-data-mining/total-year.jpg)
[Means of transport vs other ads, per year](http://www.euklides.fr/blog/altomator/Image_Retrieval/Ads-data-mining/Periodical_FR_1910-1920_ads-year.htm)

![Means of transport illustrated ads, per month](http://www.euklides.fr/blog/altomator/Image_Retrieval/Ads-data-mining/total-month.jpg)
Means of transport illustrated ads, per month: [% of published ads per page](http://www.euklides.fr/blog/altomator/Image_Retrieval/Ads-data-mining/Periodical_FR_1910-1920_mean-ads-month.htm) and [total of published ads](http://www.euklides.fr/blog/altomator/Image_Retrieval/Ads-data-mining/Periodical_FR_1910-1920_total-ads-month.htm)












 

