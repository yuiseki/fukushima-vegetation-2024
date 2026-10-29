# Fukushima extract of 現存植生図2024: verification and profile

- polygons: 336,047 (336,047 MultiPolygon), CRS EPSG:6668, bbox lon 139.1648 to 141.0461, lat 36.7913 to 37.9766
- source files: {'veg2024bk2a.gpkg': 327774, 'veg2024bk3.gpkg': 4207, 'veg2024bk4.gpkg': 4066}
- cut: 333,948 polygons wholly inside Fukushima kept as they are; 2,099 polygons that cross the boundary were clipped to it (none dropped); the clipped polygons had 2438.9 km2 before the cut and keep 851.3 km2
- area: 13780.979 km2 in EPSG:6677, against 13781.093 km2 for the N03 polygon of Fukushima (99.99917%, difference -0.114 km2)
- area by 地域ブロック: 2 東北 13292.433 km2 (96.45% of N03), 3 関東 255.267 km2 (1.85% of N03), 4 北陸 233.278 km2 (1.69% of N03)
- geometry validity: 0 invalid, 0 empty; fid unique: True
- overlaps: 212 pairs of polygons overlap by a sliver (largest 5.46e-09 square degrees, about 53 m2); not repaired
- NULLs: 0 in all columns

## 作成年度 (polygons)

| year | polygons |
| --- | ---: |
| 2000 | 26,170 |
| 2002 | 4,439 |
| 2003 | 42,517 |
| 2006 | 54,917 |
| 2009 | 11,704 |
| 2015 | 12,912 |
| 2016 | 9,706 |
| 2017 | 49,304 |
| 2018 | 41,234 |
| 2020 | 83,144 |

## Legends whose name contains ブナ, ミズナラ, ナラ or コナラ

21 of the 191 legends present in Fukushima; 62,305 polygons, 5348.7 km2 together (the legends overlap in meaning, do not read this as one class).

| code | name (original) | polygons | area km2 | ブナ | ミズナラ | ナラ | コナラ |
| --- | --- | ---: | ---: | :-: | :-: | :-: | :-: |
| 110100 | チシマザサ－ブナ群団 | 3,068 | 921.13 | x |  |  |  |
| 110103 | スギ－ブナ群落 | 200 | 5.19 | x |  |  |  |
| 110501 | ホツツジ－ミズナラ群集 | 1,138 | 64.96 |  | x | x |  |
| 130100 | スズタケ－ブナ群団 | 44 | 4.67 | x |  |  |  |
| 130103 | ミヤコザサ－ブナ群集 | 255 | 9.61 | x |  |  |  |
| 130111 | ブナ－イヌブナ群集 | 11 | 3.79 | x |  |  |  |
| 130203 | モミ－イヌブナ群集 | 23 | 1.29 | x |  |  |  |
| 130205 | アブラツツジ－イヌブナ群集 | 447 | 35.82 | x |  |  |  |
| 130601 | クリ－コナラ群集（自然林） | 229 | 15.41 |  |  | x | x |
| 190100 | ウラジロヨウラク－ミヤマナラ群団 | 2,722 | 143.43 |  |  | x |  |
| 190101 | ミヤマナラ群落 | 219 | 7.75 |  |  | x |  |
| 220100 | ブナ－ミズナラ群落 | 1,955 | 531.87 | x | x | x |  |
| 220102 | クリ－ミズナラ群集 | 4,296 | 331.03 |  | x | x |  |
| 220103 | オオバクロモジ－ミズナラ群集 | 2,559 | 900.19 |  | x | x |  |
| 220104 | ブナ二次林 | 2 | 0.03 | x |  |  |  |
| 220110 | フクオウソウ－ミズナラ群集 | 56 | 0.01 |  | x | x |  |
| 220500 | コナラ群落（V） | 1 | 0.08 |  |  | x | x |
| 220501 | オクチョウジザクラ－コナラ群集 | 4,944 | 706.92 |  |  | x | x |
| 221103 | ミヤコザサ－ミズナラ群集 | 18 | 0.68 |  | x | x |  |
| 410101 | クリ－コナラ群集 | 36,675 | 1532.58 |  |  | x | x |
| 410102 | クヌギ－コナラ群集 | 3,443 | 132.22 |  |  | x | x |

The match is by substring on the original name. ナラ also matches names that are neither ミズナラ nor コナラ: ウラジロヨウラク－ミヤマナラ群団 (190100), ミヤマナラ群落 (190101). ブナ also matches イヌブナ, another species: ブナ－イヌブナ群集 (130111), モミ－イヌブナ群集 (130203), アブラツツジ－イヌブナ群集 (130205).
The full list of Fukushima legends is `legend_fukushima.tsv`.

## 作成年度 of the polygons of those legends

| year | polygons |
| --- | ---: |
| 2000 | 3,363 |
| 2002 | 379 |
| 2003 | 6,157 |
| 2006 | 12,512 |
| 2009 | 1,774 |
| 2015 | 2,628 |
| 2016 | 3,620 |
| 2017 | 9,777 |
| 2018 | 8,610 |
| 2020 | 13,485 |
