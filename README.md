# 道路交通センサスマップ2021 on MapLibre GL JS
## Public Website
https://shi-works.github.io/road-traffic-census-map-2021/

![image](https://github.com/shi-works/road-traffic-census-map-2021/assets/71203808/ecd1029a-93e5-42e9-ad34-327d63562cfa)

## Data Source
### 全国道路・街路交通情勢調査（道路交通センサス）
- 令和3年度全国道路・街路交通情勢調査 一般交通量調査結果  
箇所別基本表 https://www.mlit.go.jp/road/census/r3/index.html  
可視化ツール https://www.mlit.go.jp/road/ir/ir-data/census_visualizationR3/index.html

## GIS Data
- 上記の可視化ツールからGISデータ（GeoJSON）を取得。
- GeoJOSNの属性「census」と箇所別基本表の「交通調査基本区間番号」をキーにして、GeoJOSNに箇所別基本表を紐づけて作成
### PMTiles形式
`https://xs489works.xsrv.jp/pmtiles-data/traffic-census/traffic_census_2021_convert.pmtiles`,719MB
### GeoParquet形式
`https://xs489works.xsrv.jp/pmtiles-data/traffic-census/traffic_census_2021_convert.parquet`,97MB
