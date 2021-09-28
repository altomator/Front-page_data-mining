# Newspapers front page: human faces data mining

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

[![Men and women faces](https://github.com/altomator/Introduction_to_Deep_Learning-2-Face_Detection/blob/main/images/faces-excelsior.jpg)](https://altomator.github.io/Introduction_to_Deep_Learning-2-Face_Detection/Excelsior/Graphes/faces-year-EN.htm)

See some samples [here](https://github.com/altomator/Introduction_to_Deep_Learning-2-Face_Detection/tree/gh-pages/Excelsior).










 

