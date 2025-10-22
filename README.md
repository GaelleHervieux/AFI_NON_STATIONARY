compute_reg_corr_DJFTemp_glost.ipynb : Compute the regression and correlation of the DJF mean/variance of daily ERA5 temperature onto the 30 year smoothed GLOST (LOESS).

Plot of evgam ERA5 AFI analysis:
| File name  |    Domain      |  Period      | Distribution |   location      |  scale |shape |
|:----------:|:-------------:|:-------------:|:-------------|:-------------|:------|:------|
| NSloc_loess   |CONUS  |1941-2023  | gev| ~ s(glost,k=5) | ~ 1 | ~1|
| NSloc_loess  |Alaska  |1941-2023 |gev|  ~ s(glost,k=5) | ~  1 | ~1|
| NSloc_sc_loess   |CONUS  |1941-2023  | gev| ~ s(glost,k=5) | ~ s(glost,k=5) | ~1|
| NSloc_sc_loess  |Alaska  |1941-2023  |gev|  ~ s(glost,k=5) | ~ s(glost,k=5) | ~1|
| NSloc_sc_loess  |CONUS  |1941-2023  | gev| ~ s(glost,k=5) | ~ s(glost,k=5) | ~1|
| NSloc_sc_loess  |Alaska  |1941-2023  |gev|  ~ s(glost,k=5) | ~ s(glost,k=5) | ~1|
 |NOS_loc_sck2_loess|CONUS  |1941-2023  | gev| ~ s(glost,k=5) | ~ s(glost,k=2) | ~1|
 |NOS_loc_sck1_loess|CONUS  |1941-2023  | gev| ~ s(glost,k=5) | ~ s(glost,k=1) | ~1|
 |NOS_loc_sck2_loess|Alaska  |1941-2023  |gev|  ~ s(glost,k=5) | ~ s(glost,k=2) | ~1|
 |NOS_loc_sck1_loess|Alaska  |1941-2023  |gev|  ~ s(glost,k=5) | ~ s(glost,k=1) | ~1|
| Weibull_NOS_sc_sh|CONUS  |1941-2023  | Weibull| na  | ~ s(glost,k=5) | ~ s(glost,k=5)|
| Weibull_NOS_sc|CONUS  |1941-2023  | Weibull| na  | ~ s(glost,k=5) | ~1|
|Weibull_NOS_sc_sh|Alaska  |1941-2023  |Weibull|  na  | ~ s(glost,k=5) | ~ s(glost,k=5)|
|Weibull_NOS_sc_sh_Alaska|Alaska  |1941-2023  |Weibull|  na  | ~ s(glost,k=5) | ~1|
