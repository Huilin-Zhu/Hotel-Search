# Hotel-Search

In this project, we utilize a dataset of a booking website, and develop a simple program in python. Our program can search and rank hotels by applying boolean IR and vector space IR techniques; in addition, it also has functionalities for hotel clustering to find the related hotels based on user selection of search results. 
* [Dataset download link](https://www.kaggle.com/jiashenliu/515k-hotelreviews-data-in-europe/version/1)

The following figure indicates the functionality areas of the search GUI. ![hotel search GUI](https://user-images.githubusercontent.com/65043460/149218794-6904a899-afd0-4999-8542-2853ba199599.jpg)

The main search engine is contained in `Program.ipynb`. The clustering visualization is contained in `kMeans_Hotel.ipynb`.

Libraries:
* sklearn
* nltk
* numpy
* pandas
* sqlite3
* tkinter 
