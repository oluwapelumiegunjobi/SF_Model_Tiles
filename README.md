# SF_Model_Tiles
XYZ Tiles of the 1940 SF Model

## Live Map URL
https://oluwapelumiegunjobi.github.io/SF_Model_Tiles/

## Tile Folder Location
The map tiles are stored inside:

/tiles/

The tile structure follows:

/tiles/{z}/{x}/{y}.png

## Updating index.html
To change the map source, edit this line inside index.html:

L.tileLayer('./tiles/{z}/{x}/{y}.png', {
    attribution: 'Map data'
}).addTo(map);
