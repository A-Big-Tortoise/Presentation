### RR Removal

| Method | Noise |  S   |  D   |
| :----: | :---: | :--: | :--: |
|  FMM   |       |      |      |
|  MMD   |       |      |      |
|  SSA   |       |      |      |
|  EEMD  |       |      |      |



### Echo Removal 

|  RR  |   Method    | Noise |  S   | D    |
| :--: | :---------: | :---: | :--: | ---- |
|  No  | HHT+ACF+FMM |       |      |      |



### Template

|  RR  |      Segmentation       |      FUshion       | NOISE | S    | D    |
| :--: | :---------------------: | :----------------: | :---: | ---- | ---- |
| Yes  | Based on Circle Length  |      K-Shape       |       |      |      |
|  No  | Based on Circle Length  |      K-Shape       |       |      |      |
| Yes  | Based on Circle Length  | K-Shape with Trick |       |      |      |
|  No  | Based on Circle Length  | K-Shape with Trick |       |      |      |
| Yes  | Based on Peak Detection |   Mean of Pieces   |       |      |      |
|  No  | Based on Peak Detection |   Mean of Pieces   |       |      |      |
| Yes  | Based on Peak Detection |  Median of Pieces  |       |      |      |
|  No  | Based on Peak Detection |  Median of Pieces  |       |      |      |
| Yes  | Based on Peak Detection | K-Shape with Trick |       |      |      |
|  No  | Based on Peak Detection | K-Shape with Trick |       |      |      |
|  No  | Based on Peak Detection |        DTW         |       |      |      |
|  No  | Based on Peak Detection |        DDTW        |       |      |      |
|  No  | Based on Peak Detection |        WDTW        |       |      |      |
|  No  | Based on Peak Detection |      shapeDTW      |       |      |      |
|  No  | Based on Peak Detection |       U-DTW        |       |      |      |
|      |                         |       US-DTW       |       |      |      |
|      |                         |        DBA         |       |      |      |
|      |                         |                    |       |      |      |
|      |                         |                    |       |      |      |
|      |                         |   Kalman Filter    |       |      |      |

