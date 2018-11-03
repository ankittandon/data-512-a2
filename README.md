# Bias in Data

Name: Ankit Tandon

Date: 11/03/2018

## Goal
The goal of this project is to explore possible bias in data from Wikipedia. In particular, we are interested in looking at how article quality varies from country to country.

## Data sources used
In this analysis we draw from 3 different data sources:
1. Wikipedia dataset on pages about political figures found from https://figshare.com/articles/Untitled_Item/5513449 
2. Article quality as judged by the ORES API. More information about this API can be found here: https://www.mediawiki.org/wiki/ORES
3. Country population data located here: https://www.dropbox.com/s/5u7sy1xt7g0oi2c/WPDS_2018_data.csv?dl=0

## Resources used
This analysis was prepared using Python 3.5 running in a Jupyter Notebook environment.  
Documentation for Python can be found here: https://docs.python.org/3.5/  
Documentation for Jupyter Notebook can be found here: http://jupyter-notebook.readthedocs.io/en/latest/  
The default package DefaultDict from the collections library was also utilitzed in this analysis.


The following Python packages were used and their documentation can be found at the accompanying links:

## Files Created
This notebook creates N CSV files of data extracted and compiled as part of this analysis.

The first file...

The Nth file...

## Visualizations Created

#top 10 countries in terms of number of politician articles as a proportion of country population
Rank	country							politician articles as a proportion of population
1		tuvalu							5500.0
2		nauru							5300.0
3		san marino						2733.3333333333335
4		monaco							1000.0
5		liechtenstein					725.0
6		tonga							630.0
7		marshall islands				616.6666666666667
8		iceland							515.0
9		andorra							425.0
10		federated states of micronesia	380.0

#bottom 10 countries in terms of number of politician articles as a proportion of country population
Rank	Country							politician articles as a proportion of population
1		india							0.7219426821264494
2		indonesia						0.8107088989441931
3		china							0.8164729516429904
4		uzbekistan						0.8814589665653496
5		ethiopia						0.9767441860465116
6		zambia							1.4689265536723164
7		korea, north					1.5234375
8		thailand						1.6918429003021147
9		bangladesh						1.9471153846153846
10		mozambique						1.9672131147540983

#top 10 countries in terms of proportion of articles that are predicted as GA or FA a.k.a good articles
Rank	Country							proportion of good articles
1		korea, north					0.15384615384615385
2		rhodesian						0.13157894736842105
3		saudi arabia					0.11764705882352941
4		central african republic		0.11764705882352941
5		romania							0.11494252873563218
6		mauritania						0.09615384615384616
7		tuvalu							0.09090909090909091
8		bhutan							0.09090909090909091
9		dominica						0.08333333333333333
10		united states					0.07468123861566485

#bottom 10 countries in terms of proportion of articles that are predicted as GA or FA a.k.a good articles
Rank		Country						proportion of good articles
1		tanzania						0.0024509803921568627
2		peru							0.002824858757062147
3		czech republic					0.003937007874015748
4		lithuania						0.004032258064516129
5		nigeria							0.0043859649122807015
6		morocco							0.004807692307692308
7		bolivia							0.0053475935828877
8		brazil							0.00539568345323741
9		luxembourg						0.005555555555555556
10		sierra leone					0.006024096385542169

## License

This assignment code is released under the MIT license

The data sources are licensed under ...