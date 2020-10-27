# SHL2020

**Team:** `RED CIRCLE`

This year's challenge <a href="http://www.shl-dataset.org/activity-recognition-challenge-2020/">link</a>.

# Content

- Feature Extraction <a href="SHL_import_featureExtraction.ipynb">Notebook</a>
- Feature Analysis <a href="SHL_featureAnalysis.ipynb">Notebook</a>
- Dataset Split and Make Batch <a href="SHL_split_and_batch.ipynb">Notebook</a>

# Feature Column Name

Column Name Format: `[channel]`_`[feature]` Example: `acc_mean`

 

## **Channel** Names - [Total: 10]

  
| Keyword | Channel Name |
| :-----: | :-------------------------------- |
|`[acc]`  | Acceleration |
|`[lacc]`  | Linear Acceleration |
|`[acch]`  | Acceleration Horizontal Component |
|`[accv]`  | Acceleration Vertical Component |
|`[jerkh]`  | Jerk Horizontal Component |
|`[jerkv]`  | Jerk Vertical Component |
|`[mag]`  | Magnetometer |
|`[gyr]`  | Gyroscope |
|`[pres]`  | Pressure |
|`[label]`  | Label |

  

## **Statistical** Features - [Total: 10]

  

| Keyword | Feature |
| :--------------:| :--------------------------- |
|`[mean]`  | Mean |
|`[std]`  | Standard Deviation |
|`[max]`  | Maximum |
|`[min]`  | Minimum |
|`[mad]`  | Median Absolude Deviation |
|`[iqr]`  | Inter Quartile Range |
|`[max.corr]`  | Max Autocorrelation |
|`[idx.max.corr]`  | Index of Max Autocorrelation |
|`[zcr]`  | Zero Crossing Rate |
|`[fzc]`  | First Zero Crossing Index |

  

## **Spectral** Features - [Total: 5]
 

| Keyword | Feature |
| :---------:| :--------------- |
|`[max.PSD]`  | Maximum PSD |
|`[entropy]`  | Entropy |
|`[fc]`  | Center Frequency |
|`[kurt]`  | Kurtosis |
|`[skew]`  | Skewness |
