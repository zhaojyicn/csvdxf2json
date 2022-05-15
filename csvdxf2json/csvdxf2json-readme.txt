csvdxf2json-readme

Transform from json-data to csv-data. 
Transform from csv-data to json-data. 
Get layers of dxf-data.
Transform from dxf-data to json-data. 

1. json  Export csv File
source json file: input\dataInJson.json
output csv file: output\datasout.csv

2. csv  Export json File
source csv file: input\dataInBLtext.csv
output json file: output\datasout.json

3. Get Layers From Dxf
Get layers of dxf. Find layers information by console.log().

4. Get Entities From Dxf
source dxf file: input\dkdatadxf.dxf
output json file: output\1652578383278.json. The file can be imported to QGIS. By modifying conversion parameter "xy4cs_Xian80ToCGCS2000 = [0,0,0,1]", change Coordinate Reference System.
