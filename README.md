# 道路交通センサスマップ2021 on MapLibre GL JS
## Public Website
https://shi-works.github.io/road-traffic-census-map-2021/

## Data Source
### 全国道路・街路交通情勢調査（道路交通センサス）
- 令和3年度全国道路・街路交通情勢調査 一般交通量調査結果  
箇所別基本表 https://www.mlit.go.jp/road/census/r3/index.html  
可視化ツール https://www.mlit.go.jp/road/ir/ir-data/census_visualizationR3/index.html

## GIS Data
- 上記の可視化ツールからGISデータ（GeoJSON）を取得して、GeoJOSNのcensus（箇所別基本表の交通調査基本区間番号）をキーにして、箇所別基本表を紐づけて作成
### PMTiles形式
`https://xs489works.xsrv.jp/pmtiles-data/traffic-census/traffic_census_2021_convert.pmtiles`,725MB
### GeoParquet形式
`https://xs489works.xsrv.jp/pmtiles-data/traffic-census/traffic_census_2021_convert.parquet`,98MB
