# Front-page-faces_data-mining

This work is a compagnon project of the [GallicaPix PoC](https://gallicapix.bnf.fr/). It leverages a dataset of heritage French periodical  built under the [GallicaPix](https://github.com/altomator/Image_Retrieval) scope.


## Face detection pipeline
Various tools have been applied to the front page illustrations of Excelsior newspaper: IBM Watson Visual Recognition, Google Cloud Vision, OpenCV/dnn. See this [github](https://github.com/altomator/Image_Retrieval). 

![Faces](https://github.com/altomator/Ads-data_mining/blob/master/ads/airplanes/airplane4.jpg)



## Analysis
The following charts mainly show the impact of the WW1 on the economy, through the quantity of ads published, and the evolution of transport techniques. 

![Means of transport vs other ads, per year](http://www.euklides.fr/blog/altomator/Image_Retrieval/Ads-data-mining/total-year.jpg)
[Means of transport vs other ads, per year](http://www.euklides.fr/blog/altomator/Image_Retrieval/Ads-data-mining/Periodical_FR_1910-1920_ads-year.htm)

![Means of transport illustrated ads, per month](http://www.euklides.fr/blog/altomator/Image_Retrieval/Ads-data-mining/total-month.jpg)
Means of transport illustrated ads, per month: [% of published ads per page](http://www.euklides.fr/blog/altomator/Image_Retrieval/Ads-data-mining/Periodical_FR_1910-1920_mean-ads-month.htm) and [total of published ads](http://www.euklides.fr/blog/altomator/Image_Retrieval/Ads-data-mining/Periodical_FR_1910-1920_total-ads-month.htm)

For example, the analysis shows that military truck stocks were massively converted to civilian use from 1919 onwards.

The insights that one may learn from these data must be mitigated by the following facts:
- the source dataset may be biased (roughly 30 titles),
- some ads may have been missed, some illustrated ads are actually editorial content,
- most of the analysis is based on object detection, which may be irrelevant in some cases (e.g. advertisements for car spare parts are not taken into account; transport ads may be purely textual)
- some of the means of transport may also be used to illustrate another context, not relevant to this analysis (e.g. sport/leisure/health)












 

