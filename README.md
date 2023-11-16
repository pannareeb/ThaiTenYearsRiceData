
 
**Descriptive statistics of two types of data sets from [Thailand Office of Agricultural Economics](https://www.oae.go.th/view/1/%E0%B8%95%E0%B8%B2%E0%B8%A3%E0%B8%B2%E0%B8%87%E0%B9%81%E0%B8%AA%E0%B8%94%E0%B8%87%E0%B8%A3%E0%B8%B2%E0%B8%A2%E0%B8%A5%E0%B8%B0%E0%B9%80%E0%B8%AD%E0%B8%B5%E0%B8%A2%E0%B8%94%E0%B8%82%E0%B9%89%E0%B8%B2%E0%B8%A7%E0%B8%99%E0%B8%B2%E0%B8%9B%E0%B8%B5/TH-TH).**

In the documents, we extract trends from data about Thai rice cultivation. Specifically, the first sheet provides yields of 12 (groups of) cultivars from harvested areas in each of 77 provinces in Thailand, and the second data sheet provides yields of rice (not separated into variaties) from fields with different planting method and seed use rate, also in each of 77 provinces. The reason why we cannot/should not use the data sets for modelling is also laid out in the files.



1. **raw-data folder:** this subfolder contains
   - 10 datasheets (.csv) of the yields of 12 Thai rice varieties (only in-season rice considered). One sheet is for one year, and the years range from 2012-2021. Together, they are processed and merged to form the first final data set.
   - list of provinces in each region of Thailand
   - 1 datasheet of yields of whole rice with planting method and seed use rate. 


*First data set: We extracted Trends of Production, Popularity, Yield of Thai rice cultivation at country and regional level* 
2. **processed-data folder:** this contain the merged cleaned spreadsheet after pre-processing
3. **TrendsfromTenYears.Rmd:** the file aims to use the 10 .csv spreadsheets of the yields in the raw-data folder for elucidate 
the general questions: what cultivars have been most grown and produced and what has given the best yield over the past 10 years, at the country-level and regional level. In what region, the study to improve yield will have a high impact.
4. **TrendsfromTenYears.html:** the knitted version of the TrendsfromTenYears.Rmd

*Second data set: We try to understand the Effect of planting methods on yields*
5. **PlantMethod.Rmd:** the file aims to answer how 4 types of planting methods (direct sowing, trasnpalnting, wet and dry broadcasting) influences the yields, and tried creating a predictive model from supposedly data least affected by confounding factors.
6.  **PlantMethod.html:** the knitted version of the PlantMethod.Rmd
