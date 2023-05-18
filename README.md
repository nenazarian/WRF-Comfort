# WRF-Comfort
To activate WRF-comfort, the following lines must be added to URBAPRM.TBL or URBPARM_LCZ.TBL

\# THERM_COMF: switch to estimate thermal comfort parameters: 0 no, 1 SET, 2 UTCI

THERM_COMF: 2

\# MET_COMF:  metabolic rate (for thermal comfort index, SET)
\#      (sf_urban_physics=3)

MET_COMF: 1.2, 1.2, 1.2, 1.2, 1.2, 1.2, 1.2, 1.2, 1.2, 1.2, 1.2

\# CLO_COMF:  clothing  (for thermal comfort index, SET)
\#      (sf_urban_physics=3)

CLO_COMF: 0.4, 0.4, 0.4, 0.4, 0.4, 0.4, 0.4, 0.4, 0.4, 0.4, 0.4

\# WME_COMF:  work  (for thermal comfort index, SET)
\#      (sf_urban_physics=3)

WME_COMF: 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0

\# WEIGHT_COMF:  body weight in Kg  (for thermal comfort index, SET)
\#      (sf_urban_physics=3)

WEIGHT_COMF: 80, 80, 80, 80, 80, 80, 80, 80, 80, 80, 80

\# HEIGHT_COMF:  body height in m  (for thermal comfort index, SET)
\#      (sf_urban_physics=3)

HEIGHT_COMF: 1.80, 1.80, 1.80, 1.80, 1.80, 1.80, 1.80, 1.80, 1.80, 1.80, 1.80
