# House Price Index Analysis Project

--- 

For this project, we analyzed the House Price Index (HPI) provided by the Federal Housing Finance Agency (FHFA). As per the FHFA, the HPI is a broad indicator of single-family house price trends at various geographic levels. The HPI can offer insights about house price fluctuations ranging from broader national level to very concise cencus tract level. We took a deeper dive into the Finance and Real Estate industries using the HPI dataset to uncover trends and insights from the HPI based on location in the U.S.

### Questions we will ask of the data:

- Are there any patterns or fluctuations in HPI based on region? How do the different regions compare?
- What is the trend in HPI pre-COVID, and to what degree did it change during COVID?
- Is there any correlation between HPI and CPI (Inflation) on a national level? What conclusions can we draw from the comparison?

### Source for the data:

Our House Price Index data will come from the [FHFA website](https://www.fhfa.gov/DataTools/Downloads/Pages/House-Price-Index-Datasets.aspx). We will be utilizing the Master HPI Data which appends quarterly and monthly data. Additionally, we will be utilizing the U.S. Bureau of Labor Statistics' Consumer Price Index dataset to answer our correlation questions. Specifically, we will utilize the [U.S. City Average, All items](https://www.bls.gov/cpi/data.htm) to gain a more broad understanding of the CPI.

#### Are there any patterns or fluctuations in HPI based on region? How do the different regions compare?

We can see that HPI trends amongst all regions in the United States are fairly similar. We can see gradual linear increase from 1990 to around 2007, and slight regression until 2012. From 2012-2023 one can observe there is significant increase in HPI in all regions. All regions followed a similar pattern of growth, just on different scales. This is particularly prevalent in the Mountain and Pacific Region of the United States.

![HPI by Region](https://github.com/wpreeti/Group-8_Project/blob/main/HpiCpi_viz/output/samoutput.png?raw=true)

#### What is the trend in HPI pre-COVID, and to what degree did it change during COVID?

HPI Rises steadly from 2017 to 2019, at and increases about

![HPI pre covid](https://github.com/wpreeti/Group-8_Project/blob/main/HpiCpi_viz/output/output5.png?raw=true)
![HPI post covid](https://github.com/wpreeti/Group-8_Project/blob/main/HpiCpi_viz/output/output6.png?raw=true)

#### Is there any correlation between HPI and CPI (Inflation) on a national level? What conclusions can we draw from the comparison?

In our exploratory analysis of the average HPI per year in the U.S., there are 3 immediate observations:
- Effect of Housing Market Crash: We saw peak unemployment and peak home foreclosures in 2010
- ~5-year dip before returning in 2016: Unemployment rate begins to recover around 2012
- Sharp increase in 2020, presumably due to the effects of covid. Further analysis of just the years of 2020-2022 would have to be conducted to pinpoint exact causes of the rise.

![HPI U.S.](https://github.com/wpreeti/Group-8_Project/blob/main/HpiCpi_viz/output/output1.png?raw=true)

In analyzing the year-over-year change percentage change, we can see make some comparisons about the changes of both the House Price Index and the Consumer Price Index. It can be observed that the spikes and dips loosely follow each other, and again we can see both the House Price Index and Inflation sharply increase after the start of COVID. From the 2020 to the 2021, the House Price Index rose 16% from the previous year. Inflation followed close behind and rose 8% from 2021 to 2022. Again, further research is needed to pinpoint the exact causes of the rise, but the year over year change does help with our exploratory analysis.

![HPI YOY](https://github.com/wpreeti/Group-8_Project/blob/main/HpiCpi_viz/output/output2.png?raw=true)

In wrapping up the exploratory analysis, I just wanted to to some testing and see just how strongly the House Price Index and Inflation was correlated. I also wanted to see if we could use the House Price Index to predict trends in inflation. House Price Index and Inflation are very strongly correlated with an r-value of 0.93, and we can confidently say that the HPI does have an effect on inflation. Going forward, we hope these visualization could help non-economist types to make more informed decisions about home-owning, especially when we can compare the House Price Index by region and make comparisons by region.

![HPI Regression](https://github.com/wpreeti/Group-8_Project/blob/main/HpiCpi_viz/output/output7.png?raw=true)
