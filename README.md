# retrieval-2016-lostobject
Time-sensitive Egocentric Image Retrieval for Fidings Objects in Lifelogs. 


|  ![CVPR 2016 logo][logo-cvpr] | Extended Abstract accepted at [4th Workshop on Egocentric (First-Person) Vision, 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)](http://www.cbi.gatech.edu/fpv2016/index.html)   |
|:-:|---|


[logo-cvpr]: https://raw.githubusercontent.com/imatge-upc/saliency-2016-cvpr/master/logos/cvpr2016.jpg "CVPR 2016 logo"

| ![Cristian Reyes][CristianReyes-photo]  | ![Kevin McGuinness][KevinMcGuinness-photo]  | ![Elisa Sayrol][ElisaSayrol-photo]  | ![Noel O'Connor][NoelOConnor-photo]  | ![Xavier Giro-i-Nieto][XavierGiro-photo]  |
|:-:|:-:|:-:|:-:|:-:|
| Cristian Reyes  |  [Elisa Sayrol][EvaMohedano-web]  | [Kevin McGuinness][KevinMcGuinness-web]   | [Noel O'Connor][NoelOConnor-web]   | [Xavier Giro-i-Nieto][XavierGiro-web]   |

[EvaMohedano-web]: https://www.insight-centre.org/users/eva-mohedano
[KevinMcGuinness-web]: https://www.insight-centre.org/users/kevin-mcguinness
[NoelOConnor-web]: https://www.insight-centre.org/users/noel-oconnor
[XavierGiro-web]: https://imatge.upc.edu/web/people/xavier-giro

[CristianReyes-photo]: https://raw.githubusercontent.com/imatge-upc/retrieval-2016-lostobject/master/authors/Cristian.jpg "Cristian Reyes"
[EvaMohedano-photo]: https://raw.githubusercontent.com/imatge-upc/retrieval-2016-lostobject/master/authors/Eva.jpg "Eva Mohedano"
[KevinMcGuinness-photo]: https://raw.githubusercontent.com/imatge-upc/retrieval-2016-lostobject/master/authors/Kevin.jpg "Kevin McGuinness"
[NoelOConnor-photo]: https://raw.githubusercontent.com/imatge-upc/retrieval-2016-lostobject/master/authors/Noel.jpg "Noel O'Connor"
[XavierGiro-photo]: https://raw.githubusercontent.com/imatge-upc/retrieval-2016-lostobject/master/authors/Xavi.jpg "Xavier Giro-i-Nieto"


A joint collaboration between:

| ![logo-insight] | ![logo-dcu] | ![logo-upc] | ![logo-etsetb] | ![logo-gpi] | 
|:-:|:-:|:-:|:-:|:-:|
| [Insight Centre for Data Analytics][insight-web] | [Dublin City University (DCU)][dcu-web]  |[Universitat Politecnica de Catalunya (UPC)][upc-web]   | [UPC ETSETB TelecomBCN][etsetb-web]  | [UPC Image Processing Group][gpi-web] | 

[insight-web]: https://www.insight-centre.org/ 
[dcu-web]: http://www.dcu.ie/
[upc-web]: http://www.upc.edu/?set_language=en 
[etsetb-web]: https://www.etsetb.upc.edu/en/ 
[gpi-web]: https://imatge.upc.edu/web/ 


[logo-insight]: https://raw.githubusercontent.com/imatge-upc/saliency-2016-cvpr/master/logos/insight.jpg "Insight Centre for Data Analytics"
[logo-dcu]: https://raw.githubusercontent.com/imatge-upc/saliency-2016-cvpr/master/logos/dcu.png "Dublin City University"
[logo-upc]: https://raw.githubusercontent.com/imatge-upc/saliency-2016-cvpr/master/logos/upc.jpg "Universitat Politecnica de Catalunya"
[logo-etsetb]: https://raw.githubusercontent.com/imatge-upc/saliency-2016-cvpr/master/logos/etsetb.png "ETSETB TelecomBCN"
[logo-gpi]: https://raw.githubusercontent.com/imatge-upc/saliency-2016-cvpr/master/logos/gpi.png "UPC Image Processing Group"


## Abstract

This work explores diverse practices for conducting an object search from large amounts of egocentric images taking into account their temporal information. The application of this technology is to identify where personal belongings were lost or forgotten. We develop a pipeline-structured system. Firstly, the images of the day being scanned are sorted based on their probability to depict the forgotten object. This stage is solved by applying an existing visual search engine based on deep learning features. Secondly, a learned threshold selects the top ranked images as candidates to contain the object. Finally the images are reranked based on temporal and diversity criteria. Furthermore, we build a validation environment for assessing the system's performance aiming to find the optimal configuration of its parameters. Due to the lack of related works to be compared with, this thesis proposes an novel evaluation framework and metric to assess the problem.

## Publication

[Our extended abstract](http://www.cbi.gatech.edu/fpv2016/abstracts/where_phone_abstract.pdf) is open published. 


![Image of the paper](https://raw.githubusercontent.com/imatge-upc/saliency-2016-cvpr/master/figs/paper.jpg)

Please cite with the following Bibtex code:

````
@article {xReyes,
	title = {Where did I leave my phone ?},
	year = {2016},
	month = {06},
	institution = {4th Workshop on Egocentric (First-Person) Vision, CVPR 2016},
	type = {Extended abstract},
	address = {Las Vegas, NV, USA},
	author = {Reyes, Cristian and Mohedano, Eva and McGuinness, Kevin and O{\textquoteright}Connor, N. and Gir{\'o}-i-Nieto, X.}
}

```

