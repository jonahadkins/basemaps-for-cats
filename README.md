basemaps-for-cats
=================

[See The Live Demo And Feel Free To Use It!](http://www.arcgis.com/home/webmap/viewer.html?webmap=c256d4a2110847aebc43ab5b9534cd87)  

Use Natural Earth `10m-admin-0-countries` layer and the following cartocss in Tilemill:

```
Map {
 background-image: url("images/white.jpg");
}
#countries{
  	[MAP_COLOR = 1 ]{ polygon-pattern-file: url("images/gray.jpg");}
  	[MAP_COLOR = 2 ]{ polygon-pattern-file: url("images/mix2.jpg");}
  	[MAP_COLOR = 3 ]{ polygon-pattern-file: url("images/brown.jpg");}
  	[MAP_COLOR = 4 ]{ polygon-pattern-file: url("images/black.jpg");}
  	[MAP_COLOR = 5 ]{ polygon-pattern-file: url("images/orange.jpg");}
   [MAP_COLOR = 6 ]{ polygon-pattern-file: url("images/gray.jpg");}
  	[MAP_COLOR = 7 ]{ polygon-pattern-file: url("images/mix2.jpg");}
  	[MAP_COLOR = 8 ]{ polygon-pattern-file: url("images/brown.jpg");}
  	[MAP_COLOR = 9 ]{ polygon-pattern-file: url("images/black.jpg");}
  	[MAP_COLOR = 10 ]{ polygon-pattern-file: url("images/orange.jpg");}
   [MAP_COLOR = 11 ]{ polygon-pattern-file: url("images/gray.jpg");}
  	[MAP_COLOR = 12 ]{ polygon-pattern-file: url("images/mix2.jpg");}
  	[MAP_COLOR = 13 ]{ polygon-pattern-file: url("images/brown.jpg");}
  [MAP_COLOR = 0 ]{ polygon-pattern-file: url("images/black.jpg");}

  }
```

publish the map with Tilemill to your MapBox account then [follow this procedure](https://github.com/jonahadkins/Custom-Basemaps-In-AGOL) to make it a basemap in AGOL

Alternatively use the [images](https://github.com/jonahadkins/basemaps-for-cats/tree/master/images) folder to experiment on your own cats.

Enjoy Your Cats!
