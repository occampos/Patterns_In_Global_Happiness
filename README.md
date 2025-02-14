[Portfolio Page](https://occampos.github.io/ChristopherCamposData/index.html)

# Patterns and Trends in Global Happiness

The World Happiness Report, a publication by the Sustainable Development Solutions Network, draws its insights from Gallup World Poll data. This report reflects on the global call for a greater emphasis on prioritizing happiness and well-being in governmental policy considerations. It measures happiness around the globe and delves into how happiness differs among individuals and nations, highlighting its significance in policymaking.

The annual happiness rankings are rooted in life evaluations conducted through the Gallup World Poll. These rankings stem from responses to the principal life evaluation question, utilizing the Cantril ladder. The Cantril ladder, also known as the Cantril Self-Anchoring Scale or the Cantril Scale, is a tool used to measure individuals' subjective well-being or life satisfaction. It was developed by psychologist Hadley Cantril in the 1960s. The scale asks respondents to imagine a ladder with steps numbered from 0 to 10, where 0 represents the worst possible life and 10 represents the best possible life. The respondents' assessments on their own current lives on this scale is the Happiness Score. Respondents are also asked additional questions, assessing their lives to derive addiotional scores such as the Social Support Score, the Freedom Score, the Generosity Score, and the Perception of Corruption Score.

This exploratory analysis draws on data from the World Happiness Report and is divided into two sections: A focused look of the year of 2023, followed by an assessment across all recorded years.

*Relveant questuons include:*

+ Does a general upward trend in happiness exist?
+ How is happiness influenced by different country features?
+ How do countries that maintain consistent levels of happiness differ from those where happiness levels constantly change?
+ Is happiness globally correlated, or does it predominantly manifest at an individual country level?
+ Can a nation experiencing unhappiness generally anticipate a progression towards higher happiness over time?

<details>
   
<summary>Conclusions</summary>

## How is happiness influenced by different country features?

In analyzing correlations from 2005 to 2023, it is evident that Log GDP per Capita(0.78), Life Expectancy(0.73), and Social Support(0.68) exhibit the strongest associations with Happiness Score while Perception of Corruption(-0.42) displays the strongest negative correlation. Freedom(0.54) also shows a positive correlation, albeit to a lesser degree and Generosity(0.17) demonstrates a slight positive relationship. This supports that on average individuals are most impacted by GDP, Life Expectancy, Social Support and Corruption and these findings are supported by the heatmap displayed in [Visual 21](#visual_21). 

The impact of country features on happiness varies between nations with high and low variance in Happiness Scores. Notably, countries with high happiness exhibit less variance, while those with lower happiness tend to display more variance. In other words, when a country attains a certain level of happiness its likely to retain that happiness, visualized in [Visual 27](#visual_27). Generally features in countries with high variance show weaker associations with happiness. This suggests that individuals in comparatively challenging situations may experience happiness regardless, while individuals in countries with higher happiness levels are more influenced by their circumstances. The relationship between Life Expectancy and Happiness Score remains consistent across both groups, indicating long lifespans as important regardless of a nation's happiness level. However, the association with Perception of Corruption differs significantly between the two groups. In countries with low variance, it is heavily negatively correlated, whereas in countries with high variance, there is no correlation. This implies that corruption has a diminished impact on individuals' lives when they face more pressing concerns and that concerns about corruption represent a luxury afforded to individuals in less problematic life situations. These findings are supported by the heatmap displayed in [Visual 28](#visual_28) and [Visual 29](#visual_29).  

## Is there a global correlation in happiness, or is happiness primarily manifested at an individual countriy level?

The Happines Score over time per nation was measured against the global average, correlation and variance was observed. Analysis reveals that global happiness trends significantly influence individual countries. [Visual 32](#visual_32) illustrates predominantly positive correlations among countries, while [Visual 33](#visual_33) emphasizes the prevalence of correlation, both positive and negative. Visual 34 highlights the mean absolute correlation of (0.421), suggesting a significant positive relationship globally. The variance of absolute correlation was measured at (0.051) showing that correlation does not differ greatly from country to country further supporting that happiness is influenced globally.

## Can a nation experiencing low happiness generally anticipate a progression towards higher happiness over time?

The global average Happiness Score appears to trend upward over time which is depicted in [Visual 19](#visual_19). Even more so, despite the pandemic, happiness levels remain relatively high compared to recent years. However, analyzing the global average may undermine patterns that are prevalent at an individual country level. By adopting a different analytical approach, a fresh perspective is unveiled. 

By subtracting the Happiness Score of a single country from its score x years in the past and aggregating these differences by the year difference (x), a nuanced understanding emerges. For instance, the difference in Happiness Score between Algeria in 2020 and Algeria in 2017, as well as between Algeria in 2016 and Algeria in 2013, is recorded as a 3 year difference. [Visual 35](#visual_35) illustrates this through boxplots, demonstrating a slight incline in the average difference in Happiness Score over time. Notably, the change in Happiness Score for any individual country is minimal, with the average score shifting less than 1 unit, while the most extreme cases witness changes closer to 3 units. Moreover, the correlation between the difference in Happiness Score and the difference in years was found to be very weak. [Visual 36](#visual_36) reveals that nations exhibit varying degrees of change over x amount of years. This all supports that a nation cannot anticipate an upward trend in happiness over time alone; rather, it is more reliant on other variables and events. Notably A signficant negative dip is observed towards the larger difference in years in both [Visual 35](#visual_35) and [Visual 36](#visual_36), this can be attested to the global pandemic occuring. Thus can be seen as an example of a larger event having more influence on happiness than time. 

## Weaknesses

Temporal Scale Limitation: <br>
The study's analysis focuses on a relatively small time space of 18 years. Trends observed within this limited time frame may not accurately represent long-term patterns and larger time scales might reveal different trends and dynamics.

Correlation vs. Causation: <br>
It's essential to recognize that correlation does not imply causation. While the study may identify correlations between variables, establishing causal relationships requires further investigation and rigorous analysis.

Ecological Fallacy: <br>
Aggregating data at the global level and correlating it with individual countries' data can lead to the ecological fallacy. This fallacy occurs when conclusions about individual-level relationships are drawn from aggregate-level data. It's crucial to acknowledge that relationships observed at the global level may not necessarily hold true for individual countries due to unique contextual factors and variations.

Lack of Contextual Analysis:
The analysis lacked deeper contextual understanding. Without additional context and qualitative insights, it is challenging to fully interpret the significance of the observed patterns and discrepancies.
</details>

<details>
   
<summary> Analysis of Happiness in 2023</summary>

### Exploring Happiness 2023
A scale is established, a happiness score surpassing 6 signifies a state of happiness, while a score below 4.5 indicates unhappiness, with scores falling in-between being categorized as moderate or indifferent.

<img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/happiness_scale.png">

The majority of countries reported a state of happiness (40.1%) or moderateness (39.4%) totaling (79.5%) as displayed in Visual 1. Conversely, a minority of the world (28 countries or 20.4%) reported unhappiness. Overall, the global trend for 2023 indicates a prevalence of moderate to higher happiness levels. Visual 2 illustrates that the majority of countries had happiness score averages ranging between 5 and 6 in 2023.

<table>
<tr><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_16.png" width="390" height="370"> </th><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_03.png"  width="411" height="370"></th></tr>
<tr><td>
   
*Visual 1; Number of countries by signal in 2023*
</td><td>
   
*Visual 2; Distriutiuon of happiness scores by number of countries in 2023* 
</td></tr> 
</table>

<p>&nbsp;</p>

Visual 3 exhibits the countries reporting the highest and lowest happiness scores in 2023. The disparity between these two groups is substantial, with the highest scores exceeding double the lowest scores in the most extreme instance. Notably, the nations attaining the highest happiness scores are predominantly located in the European region, whereas those registering the lowest scores are primarily situated in the African region. Visual 3 highlights that the disparity is hinted to be regional.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_02.png"  width="700" height="500"> | 
|:--:| 
| *Visual 3; Countries witht he highest and lowest happiness scores in 2023* | 

<p>&nbsp;</p>

Visual 4 depicts North America as having the highest average happiness score, while Africa demonstrates the lowest average happiness score. Remarkably, regions with lower average happiness scores, compared to other regions, exhibit greater variability among individual countries. For instance, the Middle East stands out with the highest variety, showcasing countries with both low and high happiness scores. 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_04.png"  width="600" height="450"> | 
|:--:| 
| *Visual 4; Happiness scores by region in 2023* | 

<p>&nbsp;</p>

Visuals 5 and 6 present the distribution of countries based on their happiness scores. Despite North America showing a high average happiness score, it only represents one country. Europe and Africa stand out in these visuals due to their higher representation. Europe hosts the most countries with higher happiness scores, while Africa contains the most countries with lower happiness scores. Visuals 5 and 6 also highlight that despite having higher or lowert scores on average each region still shows a level of diversity among scores.

<table>
<tr><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_05.png"  width="570" height="380"> </th><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_06.png"  width="570" height="380"></th></tr>
<tr><td>
   
*Visual 5; Distribution of happiness scores by region in 2023*
</td><td>
   
*Visual 6; Country feature correlations in 2023*
</td></tr> 
</table>

<p>&nbsp;</p>

Visual 7 utilizes a heatmap to demonstrate the correlation coefficients between country features in 2023. Darker shades of blue indicate stronger positive correlations, darker shades of red imply stronger negative correlations and whiter shades imply weaker correlations. Notably, variables intersecting with the Happiness score, GDP, Social support, Life expectancy, and Freedom, exhibit significantly darker shades of blue on the heatmap. This suggests a strong positive correlation among these factors, indicating they are likely to increase together. Generosity appears closer to 0, suggesting it may not have a substantial impact on other country features. Conversely, Perception of corruption is depicted as negatively correlated, supporting the notion that reduced corruption tends to correlate with higher happiness.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_07.png"  width="700" height="580"> | 
|:--:| 
| *Visual 7; Country feature correlation coefficient heatmap in 2023* | 

<p>&nbsp;</p>

Visual 9 compiles all positive correlation coefficients, showing which pairs strongly correlate with one another. In Visual 8, correlation coeffcients against happiness scores are ranked from highest to lowest. Notably, Social support exhibits the highest correlation by a considerable margin, standing at 0.83, followed by GDP at 0.78 and Life expectancy at 0.73. Although still significant, Freedom shows the least correlation among the strongly associated group at 0.66. Perception of corruption is negatively correlated but not significantly so, lying below -0.50 at -0.47.

<table>
<tr><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_17.png"  width="300" height="200"> </th><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_18.png"  width="340" height="240"></th></tr>
<tr><td>
   
*Visual 8; Country featrues correlated to happiness in 2023*
</td><td>
   
*Visual 9; Country featrues with a positive correlation coefficients in 2023*
</td></tr> 
</table>

<p>&nbsp;</p>

Visuals 10 through 15 all depict scatterplots of country features to happiness score by region in 2023. The line of best fit is included to better illustrate correlation strength which can be conveyed by how well data points fit along the line of best fit. Social support, GDP, life expectancy, and freedom all show data points that fit fairly tightly along the line of best fit with a positive slope, indicating a strong positive correlation to happiness score. Social support fits the tightest, while freedom is the most loose, which is supported by their correlation coefficients of 0.83 and 0.66 respectively. Generosity displays very loosely fitting data points, supporting a lack of correlation. Perception of corruption is the only country feature depicting a negative slope, while still falling well along the line of best fit, supporting a strong negative correlation. The scatterplot also depicts that Europe and Africa dominate world happiness, followed by Asia and Latin America. This is due to the number of countries in each region.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_08.png"  width="595" height="493"> | 
|:--:| 
| *Visual 10; Happiness score and Social support plotted by country in 2023, <br> illustrating a siginificant positive correaltion of 0.83* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_09.png"  width="595" height="493"> | 
|:--:| 
| *Visual 11; Happiness score and GDP plotted by country in 2023, <br> illustrating a positive siginificant correaltion of 0.78* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_10.png"  width="595" height="493"> | 
|:--:| 
| *Visual 12; Happiness score and Life expectancy plotted by country in 2023, <br> illustrating a siginificant positive correaltion of 0.73* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_11.png"  width="595" height="493"> | 
|:--:| 
| *Visual 13; Happiness score and Freedom plotted by country in 2023, <br> illustrating a positive siginificant correaltion of 0.66* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_12.png"  width="595" height="493"> | 
|:--:| 
| *Visual 14; Happiness score and Generosity plotted by country in 2023, <br> illustrating a lack of correlation at 0.04* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_13.png"  width="595" height="493"> | 
|:--:| 
| *Visual 15; Happiness score and Perception of Corruption plotted by country in 2023, <br> illustrating a negative correaltion of -0.47* | 

</details>

### Analysis of Happiness in All Recorded Years

The World Happiness Report covers data from 2005 to 2023, encompassing a total of 18 years. Visual 16 showcases the frequency of reports over time, with each report representing an individual country. The number of reports saw a gradual increase from 2006, reaching an average of 142.33 reports between 2011 and 2019. However, a substantial drop occurred during 2020, 2021, and 2022, followed by a resurgence of reports in 2023. This decline is possibly attributed to countries focusing on global instability during the COVID-19 pandemic, gradually resuming report submissions in 2023.

| <img src="https://github.com/occampos/Patterns_In_Happiness/blob/main/Visuals/data_all_years/data_all_years_01.png"  width="700" height="550"> | 
|:--:| 
| *Visual 16; Countries reported over time* | 

<p>&nbsp;</p>

A total of 165 countries are represented across the 18-year period. In Visual 17 and 18, the number of reports by the number of countries is detailed. The visualization indicates that the majority of countries have consistently reported every year for the entire span of 18 years, with most nations contributing data for at least 15 years.

<table>
<tr><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_03.png" width="595" height="493"> </th><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_02.png" width="200" height="500"> </th></tr>
<tr><td>
   
*Visual 17; Number of reports by the number of countries*
</td><td>
   
*Visual 18; Table of number of reports by the number of countries*
</td></tr> 
</table>

<p>&nbsp;</p>

Visual 19 shows that until 2019, there had been a general upward trend in the overall happiness of recorded countries worldwide. However, the onset of the COVID pandemic in the year 2020 can be said to have significantly impacted global happiness levels, leading to a notable decline in global happiness. According to the data provided, an indiciation on a rebound in happines after the decline has yet to be observed. 

<a id="visual_19"></a>
| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_04.png" width="800" height="600"> | 
|:--:| 
| *Visual 19; Global happiness over time* | 

<p>&nbsp;</p>

The global trend of happiness differs greatly from regional trends. Visual 20 highlights this difference by plotting happiness over time by region. North America contains the fewest countries but maintains the highest average happiness score, while Africa retained the lowest average happiness score. Interestingly, in 2020, certain regions reacted differently to the COVID pandemic compared to the global trend, which experienced a significant decline in happiness scores. Europe had an insignificant shift in happiness during this time, while Latin/South America actually had an increase. In 2020, Latin/South America experienced an increase in average happiness scores despite other regions experiencing a stark decline.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_05.png" width="800" height="600"> | 
|:--:| 
| *Visual 20; Happiness over time by region* | 

<p>&nbsp;</p>

### How is happiness influenced by different country features?

The country feature correlation matrix for all recorded years, depicted by Visual 21, looks very similar to the correlation matrix in 2023 (Visual 7). The same country features (GDP, social support, life expectancy and freedom) are shown to be correlated with happiness. Similarly to 2023, generosity has a slight correlation, while perception of corruption has a notable negative correlation. However by plotting each country feature against happiness additional insights and trends are observed.

<a id="visual_21"></a>
| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_06.png" width="700" height="580"> | 
|:--:| 
| *Visual 21; Country feature correlation heatmap in all recorded years* | 

<p>&nbsp;</p>

Visuals 22 through 26 are scatterplots of country features correlated to happiness by region for all recorded years. Similarly to 2023, social support, GDP, life expectancy, and freedom all indicate a positive correlation to the happiness score. However, GDP has barely surpassed social support as the most correlated with coefficients at 0.78 and 0.73 respectively. GDP's data points fit the line of best fit the tightest, hence a stronger correlation. Generosity is shown to have a very loose fit, supporting a lack of correlation to happiness, and Perception of Corruption shows a negative correlation.

| <img src="https://github.com/occampos/Patterns_In_Happiness/blob/main/Visuals/data_all_years/data_all_years_08.png" width="700" height="600"> | 
|:--:| 
| *Visual 22; Happiness score and GDP plotted by country for all recorded years, <br> illustrating a positive siginificant correaltion of 0.78* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_07.png" width="700" height="600"> | 
|:--:| 
| *Visual 23; Happiness score and Social support plotted by country for all recorded years, <br> illustrating a siginificant positive correaltion of 0.73* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_09.png" width="700" height="600"> | 
|:--:| 
| *Visual 24; Happiness score and Life expectancy plotted by country for all recorded years, <br> illustrating a siginificant positive correaltion of 0.68* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_10.png" width="700" height="600"> | 
|:--:| 
| *Visual 24; Happiness score and Freedom plotted by country for all recorded years, <br> illustrating a positive siginificant correaltion of 0.54* | 

<p>&nbsp;</p>

Interestingly, a distinct U shaped pattern can be seen in the plot for Generosity against Happiness Score. This supports that Generosity has less value to happiness when happiness is growing or at an average and more value to happiness when happiness is at it's or at it's highest.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_11.png" width="700" height="600"> | 
|:--:| 
| *Visual 25*; Happiness score and Generosity plotted by country for all recorded years, <br> illustrating a lack of correlation at 0.17 | 

<p>&nbsp;</p>

Additionally, a steep drop-off of Perception of Corruption is observed after around a Happiness Score of 6.5. This supports that for a country to have the greatest likelihood of achieving the highest happiness levels, the country's Perception of Corruption should fall. However, this also shows that Perception of Corruption isn't valued as much comparatively until a certain level of happiness is achieved.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_12.png" width="700" height="600"> | 
|:--:| 
| *Visual 26; Happiness score and Perception of Corruption plotted by country for all recorded years, <br> illustrating a negative correaltion of -0.43* | 

<p>&nbsp;</p>

### How do countries that maintain consistent levels of happiness differ from those where happiness levels constantly change?

Variance describes the spread of a set of values in a dataset. It quantifies how far numbers in a dataset are from the mean and provides insight into the degree to which data points differ from one another. To help understand what drives an increase in happiness in a country, I divided the nations into two groups: those with the highest variance (indicating unstable happiness) and those with the lowest variance (indicating stable happiness). Visual 27 compares the Happiness Score of those groups with the global average over time. It can be seen that countries with the most variance have a lower average happiness than both the global average and countries with the least variance. This supports that as a country reaches a certain level of happiness it is likely to maintain that happiness.

<a id="visual_27"></a>
| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_13.png" width="800" height="600"> | 
|:--:| 
| *Visual 27; Average happiness in countries with highest variance and lowest variance* | 

<p>&nbsp;</p>

Visual 28 and 29 illustrate correlations between features for the highest variance and lowest variance countries through heatmaps. Happiness Score, GDP, Social Support, and Life Expectancy remain positively correlated to one another in both of the two groups, albeit the lowest variance countries have a noticeably weaker correlation in general. <br> 
Notably, Generosity is negatively correlated to GDP and Social Support when variance is high, while there is little correlation when variance is low. This hints that Generosity is impactful only when countries are experiencing instability in happiness (when happines is likely to be lower). <br> 
Freedom shifts from being positively correlated to most features in low variation countries to a much weaker correlation in high variance countries. This supports that Freedom plays a less impactful role in happiness when countries have variable happiness (when happines is likely to be lower). <br> 
Similarly, Perception of Corruption also experiences a shift from strong correlation (negative) to a much weaker correlation in countries with variable happiness.

<a id="visual_28"></a>
| <img src="https://github.com/occampos/Patterns_In_Happiness/blob/main/Visuals/data_all_years/data_all_years_14.png" width="700" height="580"> | 
|:--:| 
| *Visual 28; Country feature correlation heatmap for countries with lowest varaince in happiness* | 

<a id="visual_29"></a>
| <img src="https://github.com/occampos/Patterns_In_Happiness/blob/main/Visuals/data_all_years/data_all_years_15.png" width="700" height="580"> | 
|:--:| 
| *Visual 29; Country feature correlation heatmap for countries with highest varaince in happiness* | 

<p>&nbsp;</p>

Visual 30 higlights the difference between correlation in happiness between the two groups. Interestingly, Perception of Corruption has the greatest difference in correlation at a change of 0.58. This supports the idea that corruption has a smaller impact on happiness in countries that do not have stable happiness, and once a country reaches a certain level of happiness and thus less problems are immediately present, then corruption has a larger effect on happiness. The same can be said for Freedom and GDP, to a less significant extent, at differences of 0.35 and 0.26 respectively. Social Support, Generosity, and Life Expectancy show insignificant differences in correlation between the two groups. <br>
Visuals 28, 29, and 30 suggest that in countries where variance in happiness is high, and thus a combination of problems exists, Freedom and Corruption are not prioritized, while Generosity is immediately noticed. In contrast, in countries where variance in happiness is low and fewer problems are present in every day life, Generosity has less of a noticeable impact, and attention can be focused on Freedom and Corruption on a larger scale.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_16.png" width="546" height="215"> | 
|:--:| 
| *Visual 30; Country feature correlation heatmap for countries with highest varaince in happiness* | 

<p>&nbsp;</p>

### Is happiness globally correlated, or does it predominantly manifest at an individual country level?

Can a country's happiness be traced to wider global happiness trends, or does it predominantly hinge on the unique circumstances within that country? Visual 31 illustrates the Happiness Score over time for individual countries (black) contrasted with the global average (yellow). Initially, there seem to be no discernible patterns, giving the appearance of a disorganized jumble. Based on this visual, one might assume that a country's happiness is disconnected from the global average.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_18.png" width="800" height="600">> | 
|:--:| 
| *Visual 31; Happiness over time by country compared to the global average shown in yellow* | 

<p>&nbsp;</p>

By examining correlation from a different perspective, a new pattern emerges. Visual 32 arranges the correlation from the most positive to the most negative, whereas Visual 33 organizes the absolute correlation from the highest to the lowest. Despite countries' diversity in correlation, it's clearly seen in Visual 32 that, on average, correlations tend to be mostly positive. Visual 33 emphasizes the prevalence of correlation, whether negative or positive. The number of countries with an absolute correlation of less than 0.2 is substantially fewer compared to those exceeding 0.2. These observations support that individual countries are significantly influenced by global happiness trends.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_19.png" width="847" height="600"> | 
|:--:| 
| *Visual 32; Individual country happiness correlation to global average happiness* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_20.png" width="847" height="600"> | 
|:--:| 
| *Visual 33; Individual country happiness correlation to global average happiness* | 

<p>&nbsp;</p>

It's expected to see a correlation of some degree because the global average is composed of all recorded countries combined. However, the magnitude becomes evident in visual 34, which also accounts for variance. The mean absolute correlation stands at a level of 0.421, signifying a significant positive relationship. Moreover, the absolute correlation demonstrates minimal variance at 0.051, indicating that country correlations exhibit slight differences from each other. This further supports that countries are influenced by the global average consistently. Solely relying on correlation and not taking into account absolute value might lead to misinterpretation, as the correlation variance is notably different at 0.202 compared to the absolute value correlation variance at 0.051.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_21.png" width="248" height="238"> | 
|:--:| 
| *Visual 34; Individual country happiness correlation to global average happiness* | 

<p>&nbsp;</p>

### Can a nation experiencing unhappiness anticipate a progression towards greater happiness over time?

This question can be studied by focusing on patterns arising after a certain amount of years. Is an outcome commonplace after just two years? or does a prevalent pattern emerge after 15 years? <br>
Immediately the correlation coefficient between the difference in happiness and the difference in years is 0.052501, which is very weak positive relationship.
The Happiness Score of a single country was subtracted from its score x years in the past, and these differences were aggregated by the year difference (x). For instance, the difference in Happiness Score between Algeria in 2020 and Algeria in 2017, as well as between Algeria in 2016 and Algeria in 2013, is recorded as a 3-year difference. Visual 35 shows this using boxplots and a line a y=0 is included to highlight change overtime. An interesting observation is that it is rare or difficult for a nation's happiness score to see significant change, whether the difference is 2 years or 17 years. The largest changes are around 3 units, while the average is much closer to 0 units, which is barely any change at all. This hints that happiness in a country is a very large-scale and complex problem that requires decades to affect. Initially a very small but consistent trend upward is seen globally. As the difference in years increases the differences in happiness also trends upward albeit very minimally. When the difference of years reaches 18 a significant spike downwards occurs. This can be interpreted as nations having a weak relationship between happiness and time and is overpowered by other factors or major events such as a pandemic.

<a id="visual_35"></a>
| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_22.png" width="800" height="600"> | 
|:--:| 
| *Visual 35; Difference in Happiness Score Over Time* |

Visual 36 reveals a closer look at the difference in happiness score over time by highlighting regional patterns. South/Central America has the most notable increase, showing a difference in happiness over time that is much more significant than any other region. While the Middle East is shown to slowly regress lower, much more than any other region. A shared trait of almost all regions is that the most recent year shows a spike downward possibly due to the pandemic. This hints that the pandemic had a major impact on happiness in a nation so much so that it decreases happiness lower than over a decade prior. This again supports that there is a relationship between happiness and time but it is very weak and can be overtaken by more impactful variables.

<a id="visual_36"></a>
| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_23.png" width="800" height="600"> | 
|:--:| 
| *Visual 36; Average Difference in Happiness Score Over Time by Region* | 
