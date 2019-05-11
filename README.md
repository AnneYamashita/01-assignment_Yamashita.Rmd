# 01-assignment_Yamashita.Rmd
"Hello, World"


## What is the admission rate and SAT average of Carnegie Mellon University
> sc%>%filter(instnm=="Carnegie Mellon University")%>%select(instnm,adm_rate,sat_avg )

# A tibble: 1 x 3
  instnm                     adm_rate sat_avg
  <chr>                         <dbl>   <dbl>
1 Carnegie Mellon University    0.363    1392

