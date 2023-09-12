# How Does COVID Influence Our Travel And Cargo Transportation
### Jack Liu

#### Abstract
COVID is the most intractable issue we need to deal with in recent times. So, this report investigate how does COVID influence our travel, cargo transportation and which city were affected the most. In this report I use air routes data from 2018 to 2021 and descriptive statistics and reduction rate to make analysis. The result show COVID have a huge negative impace on our travel but positive impact on the cargo transportation.

#### Copyright
This project uses MIT License which gives permission and rights
to use, copy, modify, merge, publish, distribute, sublicense, etc. this project. To see more details please check license file

#### How to run the project
- Download all the files in this repo and run `final_project.ipynb` step by step.
- First need to install geopandas, pandas, seaborn, matplotlib.pyplot library in local. Or run the project on https://jupyter.rttl.uw.edu/2022-spring-hcde-410-a/hub/user-redirect/lab/tree/HCDE410SP22/final_project/final_project.ipynb (only for UW and map part might not work because their is no geopanda in the jupyter hub)
- All the files written in the relevant path. If some parts do not work, replace them with an absolute path.


#### Dataset
- The 4 main datasets I use for analysis are `flight_2018.csv`, `flight_2019.csv`, `flight_2020.csv`, `flight_2021.csv`. They are all coming from [Bureau of Transportation Statistics](https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=GED&QO_fu146_anzr=Nv4%20Pn44vr45). [Here](https://www.bts.gov/learn-about-bts-and-our-work/about-bts/legislative-mandates) are their legislative mandates which state how they can collect data and there are **no copyright restrictions** on Department of Transportation (DOT) publications data. More details can be found [here](https://transportation.libanswers.com/faq/156950)
- Secondary data, in the folder `map`, I use contains U.S map information. The dataset comes from [National  Weather Service](https://www.weather.gov/gis/USStates). The copyright is AMS Copyright. Permission to use figures, tables, and brief excerpts from this work in scientific and educational works is hereby granted provided that the source is acknowledged. [Here](https://www.weather.gov/mlb/ams_copyright_notice) are the full details about their copyright.
- I also use a [chinese source](https://baijiahao.baidu.com/s?id=1728787497302380294&wfr=spider&for=pc) which describe how COVID impact China
