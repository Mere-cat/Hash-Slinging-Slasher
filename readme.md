# Hash-Slinging Slasher
預測房價區間，

## Evaluation
使用  Winkler Interval score：
![alt text](img/image.png)

where y is the true value, u is the upper prediction interval, l is the lower prediction interval, and alpha is (100-coverage%)/100.

也就是，

### Coverage

In this competition the aim is a nominal marginal coverage of 90% (i.e.
**alpha = 0.1**). That is to say that 90% of the prediction intervals contain the true value (y_true).

## Submission file format
你要預測的是每個物件的上下限（而不是單一數值）：
```
id,pi_lower,pi_upper
200000,18000.6,24000.5
200001,21000.3,26000.7
200002,2000.9,4000.1
...
```

## Features
* 'sale_date'
* 'sale_price'
* 'sale_nbr'
* 'sale_warning'
* 'join_status',
* 'join_year'
* 'latitude'
* 'longitude'
* 'area'
* 'city'
* 'zoning'
* 'subdivision'
* 'present_use'
* 'land_val'
* 'imp_val'
* 'year_built'
* 'year_reno'
* 'sqft_lot'
* 'sqft'
* 'sqft_1'

'sqft_fbsmt', 'grade',
       'fbsmt_grade', 'condition', 'stories', 'beds', 'bath_full', 'bath_3qtr',
       'bath_half', 'garb_sqft', 'gara_sqft', 'wfnt', 'golf', 'greenbelt',
       'noise_traffic', 'view_rainier', 'view_olympics', 'view_cascades',
       'view_territorial', 'view_skyline', 'view_sound', 'view_lakewash',
       'view_lakesamm', 'view_otherwater', 'view_other', 'submarket'