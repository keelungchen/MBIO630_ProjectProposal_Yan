MBIO630_ProjectProporsal_Yan
================
Yan
2022-10-04

## Research questions

1.  How is the **morphology of fringing reefs** distributed
    geographically? What are the differences along the parallel and
    vertical of the latitude?

2.  Could we estimate the **environmental conditions**, such as SST and
    wave energy or wave height, by the morphology of fringing reefs?

3.  Is the morphology of fringing reefs correlated with the
    **biodiversity**?

4.  What is the **relation** between morphology of fringing reefs,
    environmental conditions and biodiversity?

## Rationale for that question

Fringing reefs are widely distributed in the tropical and subtropical
zones across the world. The structure of fringing reefs provide the
habitats for the intertidal and subtidal organisms (*Menard et
al. 2012*). Meanwhile, the morphology of fringing reefs are shaped by
the reef-building organisms and the environment factors (*Duce et
al. 2016*). Previous researches have studied the growth and morphology
of fringing reefs from geology aspect (*Kennedy and Woodroffe 2002*) and
the bathymetric distribution of corals on the fringing reefs (*Dai
1993*). But the connection between biodiversity and morphology of
fringing reefs and their geographical differences has not been studied.

Fringing reefs can be easily observed from the satellite images in
Google Earth. The differences of fringing reefs can be observed along
the latitude (*Fig 1.*) or the different side of island. In this
project, we would quantify several morphological traits of fringing
reefs and try to explore their connection with environmental factors and
biology. The spurs and grooves are the most distinct features in the
fringing reefs. Therefore, our measurement would base on the
morphological traits of the grooves. The assumptions are shown in *Table
1*.

------------------------------------------------------------------------

![Fig1](data/Fig1.png)

##### Fig 1. The latitudial differences of fringing reefs in Taiwan.

------------------------------------------------------------------------

##### Table 1. Morphological traits of fringing reefs and their environmental or biological meanings.

| Morphological traits   | Environmental or Biological meanings                                                                     |
|:-----------------------|:---------------------------------------------------------------------------------------------------------|
| Width of groove        | narrow groove provide better shelter to avoid predators and physical disturbance                         |
| Length of groove       | longer groove means better connectivity between intertidal and subtidal zone                             |
| Density of groove      | higher density means more space can be utilized bu organisms                                             |
| Diversity of groove    | higher diversity means more niches can be utilized by different species                                  |
| Width of fringing reef | larger width means the reef building process is better, which also means warmer SST and less wave energy |

------------------------------------------------------------------------

能否計算線形的碎形維度?

看群礁的型態是否有助於生物多樣性維持 其他擾動對於其影響
了解其在南北緯度上分布的界線 有助於海域資源管理 以及保育區規劃
如果不能有效預測生物多樣性 也可當棲地評估資料 也能為數學模式提供更多資料

討論上述問題的順序

沒有絕對好的形態 要看當地的條件

## Data sources

Taiwan would be an ideal preliminary study site for this project.
Because there are well-developed fringing reefs and sufficient
biological and environmental data can be accessed.

1.  Satellite images:

-   Google Earth
-   Planet Explorer

2.  Environmental data:

-   [Earth Engine Data
    Catalog](https://developers.google.com/earth-engine/datasets/catalog)
-   [Central Weather Bureau, Taiwan
    Government](https://www.cwb.gov.tw/V8/C/)
-   [Ocean Data Bank, National Science and Technology Council,
    Taiwan](https://www.odb.ntu.edu.tw/)

3.  Biological data:

-   [IOCEAN, Ocean Affairs Council, Taiwan
    Government](https://iocean.oca.gov.tw/iOceanMap/map.aspx)
-   Local references or monitoring projects

## Proposed methods for data extraction and analysis

-   Morphological traits of fringing reefs and their geographical
    location can be extracted directly by Google Earth or using **QGIS**
    by downloading the satellite images. They can be calculated by
    creating line features. For quantifying the morphological
    differences, the **resolution of images are needed to be greater
    than 3 m/pix**.

-   Some morphological traits (such as density of groove) might be
    measured more efficiently by applying the **machine learning**.

-   By adjusting the **bands in the satellite images**. Morphological
    features might be extracted more easily.

QGIS 圖示

## Limitation

當和生物多樣性指標做分析時，會有更多其他因子影響(如
人為活動或自然史)，因此最好選沒有人為活動的區域 需要結合更精確地水下資料
生物多樣性資料應該要 看長期的波動 求其穩定性 不可只看一個時間點的值
水面上的結構是否與水下的有關? 需要現地或長期的生物調查資料支持更好
如何從不同尺度進行評估，考慮和沙子的組成，形態的多樣性?

However, the structure of fringing reefs can be complicated and have
variable components. For example, some fringing reefs have lagoon and
some of them have extended reef flat (Fig).

## Reference

[Dai, C. F. (1993). Patterns of coral distribution and benthic space
partitioning on the fringing reefs of southern Taiwan. Marine Ecology,
14(3), 185-204.](https://doi.org/10.1111/j.1439-0485.1993.tb00479.x)

[Duce, S., Vila-Concejo, A., Hamylton, S. M., Webster, J. M., Bruce, E.,
& Beaman, R. J. (2016). A morphometric assessment and classification of
coral reef spur and groove morphology. Geomorphology, 265,
68-83.](https://doi.org/10.1016/j.geomorph.2016.04.018)

[Kennedy, D. M., & Woodroffe, C. D. (2002). Fringing reef growth and
morphology: a review. Earth-Science Reviews, 57(3-4),
255-277.](https://doi.org/10.1016/S0012-8252(01)00077-0)

[Menard, A., Turgeon, K., Roche, D. G., Binning, S. A., & Kramer, D. L.
(2012). Shelters and their use by fishes on fringing coral reefs. PloS
one, 7(6), e38450.](https://doi.org/10.1371/journal.pone.0038450)

## etc
