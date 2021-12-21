# Farms-Food-Insecurity-Overlap
Final project for UKy MAP671

## About Map: 
Shows both crop land cover areas and percentage of households by county receiving SNAP benefits to highlight places where food insecurity and agriculture are simultaneously prevelant. 

## Data sources:
ESRI Land Cover GeoTiffs [(About)](https://www.arcgis.com/home/item.html?id=fc92d38533d440078f17678ebc20e8e2)     [(Download Here)](https://www.arcgis.com/apps/instant/media/index.html?appid=fc92d38533d440078f17678ebc20e8e2)

I used tiles: 15T-19T, 15S-18S, and 15R-17R to cover the eastern US.



NHGIS IPUMS [(About)](hhttps://www.nhgis.org)

I downloaded the county data for Public Assistance from American Community Survey 2019, reflecting data 2015-2019. I used both Households Receiving Public Asssistance and Households Receiving Public Assistance OR Food Stamps. I subtracted the former from the latter to isolate SNAP beneficiary households. Shapefiles also from this source. 