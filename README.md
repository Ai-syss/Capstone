# World Happiness Report Analysis

Applied data science capstone project

## Introduction

Measurements of well-being is used effectively to assess progress of countries. Lately reports on happiness of citizens has been used to guide policy-making decisions in many countries. This project aims to find correlation between economy, social support, degree of liberation, health, perception of corruption and **'Happiness score'** of countries. This will provide valuable insights about main factor leading to happiness as well as unhappiness globally. 

Though happiness of an indivial might depend on mental health, attitude and personal issues, this project focuses on happiness at a collective level which will suggest areas where the government can step in and help improve happiness of its citizens.

## Description of Data

The World Happiness Report of 153 countries was released at the United Nations on International Day of Happiness Event. It ranks 153 countries by their happiness levels. The happiness scores and rankings use data from the Gallup World Poll. The scores are based on answers to the main life evaluation question asked in the poll. This question, known as the Cantril ladder, asks respondents to think of a ladder with the best possible life for them being a 10 and the worst possible life being a 0 and to rate their own current lives on that scale. The columns following the happiness score estimate the extent to which each of six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity – contribute to making life evaluations higher in each country.

<table>
  <thead>
    <tr>
      <th>Column Name</th>
      <th>Column Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Country</td>
      <td>Name of country</td>
    </tr>
    <tr>
      <td>Regional indicator</td>
      <td>Region where the country belongs</td>
    </tr>
    <tr>
      <td>Happiness score</td>
      <td>A metric measured by asking the sampled people the question: "How would you rate your happiness on a scale of 0 to 10 where 10 is the happiest."</td>
    </tr>
    <tr>
      <td>Logged GDP per capita</td>
      <td>The extent to which GDP contributes to the calculation of the Happiness Score</td>
    </tr>
    <tr>
      <td>Social support</td>
      <td>The extent to which Family and friends contribute to the calculation of the Happiness Score</td>
    </tr>
    <tr>
      <td>Healthy life expectancy</td>
      <td>The extent to which Life expectancy contributed to the calculation of the Happiness Score</td>
    </tr>
    <tr>
      <td>Freedom to make life choices</td>
      <td>The extent to which Freedom contributed to the calculation of the Happiness Score</td>
    </tr>
    <tr>
      <td>Generosity</td>
      <td>The extent to which generosity of people contributed to the calculation of the Happiness Score</td>
    </tr>
     <tr>
      <td>Perceptions of corruption</td>
      <td>The extent to which Perception of Corruption contributes to Happiness Score</td>
    </tr>
  </tbody>
  
  ## Visualization
  
  ### Happiness score of Different Countries
  
  ![](https://github.com/Ai-syss/Capstone/blob/master/img/HappinessScore20countries.PNG)
  
  This represents the Happiness scores of top 20 countries. The happiness scores of these countries range closely between 7 and 8.
  
## Happiness score by Region

![](https://github.com/Ai-syss/Capstone/blob/master/img/Happinessbyregion.PNG)

This represents the Happiness scores by region of the 153 countries with the highest being for North America and ANZ, Western Europe, Latin America and Caribbean.

## Factors affecting Happiness score in Denmark

![](https://github.com/Ai-syss/Capstone/blob/master/img/denmark.PNG)

This shows the degree in which the six factors considered affect the happiness score in a country with a high happiness score. Freedom to make life choices and social support affect the happiness score the most.

## Factors affecting Happiness score in Afghanistan

![](https://github.com/Ai-syss/Capstone/blob/master/img/Afganisthan.PNG)

This shows the degree in which the six factors considered affect the happiness score in a country with least happiness score. Generosity and social support affect the happiness score the most.

## Happiness score & Social support

![](https://github.com/Ai-syss/Capstone/blob/master/img/RegressionPlot(Social_supportVsHappinessScore).PNG)

This shows the relationship between Happiness score and the factor that affects it the most ‘Social support’.

## Happiness score & Perceptions of corruption

![](https://github.com/Ai-syss/Capstone/blob/master/img/HapscreVsCorruption.PNG)

This shows the relationship between Happiness score and the factor that affects it the least ‘Perceptions of corruption’.

## 




  
  
