# 2019 Loksabha Elections of India
Archiving Indian Election Data

This is a compilation of 2019 Lok Sabha results. All the constituencies are combined into one file (with CSV format).

The data was downloaded and cleaned  from http://results.eci.gov.in/pc/en/constituencywise/ConstituencywiseU011.htm?ac=1
using R-ecosystem's tidyverse (rvest, tidyr, dplyr, readr, purrr, stringr) 

The variables in this file are as follows

The following nine variables are taken as it is from the website


 1) **osn**          : int  1 2 3 4 5 6 7 8 9 10 ...
 2) **conti_name**   : chr  "Andaman & Nicobar Islands-Andaman & Nicobar Islands" ... 
 3) **candidate**    : chr  "AYAN MANDAL" "KULDEEP RAI SHARMA" "PRAKASH MINJ" "VISHAL JOLLY" ...
 4) **party**        : chr  "All India Trinamool Congress" "Indian National Congress" "Bahujan Samaj Party" "Bharatiya Janata Party" ...
 5) **total_votes**  : int  1721 95308 2486 93901 2839 212 275 306 221 5341 ...
 6) **pct_votes**    : num  0.83 45.98 1.2 45.3 1.37 ...
 7) **evm_votes**    : int  1717 95249 2478 93772 2837 212 269 305 221 5339 ...
 8) **postal_votes** : int  4 59 8 129 2 0 6 1 0 2 ...
 9) **migrant_votes**: int  NA NA NA NA NA NA NA NA NA NA ...
 

The following three variables are created, xrow_id is unique for each row, x_group_id unique for each constituency and finally xconti_total is sum of all votes for the constituency

 10) **xrow_id**      : int  1 2 3 4 5 6 7 8 9 10 ...
 11) **xgroup_id**    : int  1 1 1 1 1 1 1 1 1 1 ...
 12) **xconti_total** : int  207296 207296 207296 207296 207296 207296 207296 207296 207296 207296 ...
 
 
 Note:
 These were downloaded during last of May and first week of June, 2019. Would appreciate, if you can alert me to any discrepancies.
 
 
 
