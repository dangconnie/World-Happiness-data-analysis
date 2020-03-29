# Data Analysis Practice 

## Overview

I'm learning data analysis through a Discord channel that I found through Reddit. Each week will feature a different exploratory analysis project along with data cleaning, visualization practice, statistical analysis and data storytelling. Most if not all of the datasets will be from Kaggle.

This week's project analyzes how certain factors influence a country's happiness. The dataset that we will be working with is from Kaggle. The data has been modified to contain only data from 2015 to 2017. This report ranks 155 countries by their happiness level through 6 indicators:

* economic production
* social support
* life expectancy
* freedom
* absence of corruption
* generosity
* dystopia residual

### Understanding the column data

* Country
* Happiness rank
* Happiness score
   - This is obtained from a sample of population. The survey-taker asked the respondent to rate their happiness from 1 to 10.
* Economic (GDP per cap)
   - To what extent does GDP contribute to the happiness score
* Family
   - To what extent does family contribute to the happiness score
* Health
   - To what extent does health (life expectancy) contribute to the happiness score
* Freedom
   - To what extent does freedom contribute to the happiness score. Freedom in this context represents the freedom of speech, freedom to pursue what we want, etc
* Trust (Government corruption)
   - To what extent does trust (government corruption) contribute to the happiness score
* Generosity
   - To what extent does generosity contribute to the happiness score
* Dystopia residual
   - Dystopia residual is "the Dystopia Happiness Score(1.85) + the Residual value or the unexplained value for each country". Dystopia is a made up country that has the world's least happiest people. This made up country is high in corruption, low in average income, employment, etc. Dystopia residual is used as a benchmark and should be used side-by-side with the happiness score.
     * Low dystopia residual = low level of happiness
     * High dystopia residual = high level of happiness
* Year

Do note:
𝐻𝑎𝑝𝑝𝑖𝑛𝑒𝑠𝑠𝑆𝑐𝑜𝑟𝑒=𝐸𝑐𝑜𝑛𝑜𝑚𝑖𝑐(𝐺𝐷𝑃𝑝𝑒𝑟𝑐𝑎𝑝)+𝐹𝑎𝑚𝑖𝑙𝑦+𝐻𝑒𝑎𝑙𝑡ℎ+𝐹𝑟𝑒𝑒𝑑𝑜𝑚+𝑇𝑟𝑢𝑠𝑡+𝐺𝑒𝑛𝑒𝑟𝑜𝑠𝑖𝑡𝑦+𝐷𝑦𝑠𝑡𝑜𝑝𝑖𝑎𝑅𝑒𝑠𝑖𝑑𝑢𝑎𝑙


## GitHub Link
[World Happiness Analysis](https://github.com/dangconnie/World-Happiness-data-analysis)


## Table of Contents

[Description/Overview](#overview) | [GitHub Link](#github-link) | [Table of Contents](#table-of-contents) | [Technologies](#skills-and-technologies) | [Results](#Results)


## Skills and Technologies
The following skills and technologies were used:

   * Python
   
   * Data cleaning
   
   * Exploratory data analysis
   
   * Data visualization
   
   * Statistical analysis
   
   * Data storytelling
   
   * Kaggle
   
   * Jupyter Notebook/Google Colab
   

## Results
Economy, health and family have the highest impact on a country's happiness score. Freedom and dystopia residual have moderate impacts while Trust and Generosity are the least impactful on a country's happiness score. 

*   Economy: If you live in a country with a better economy, you have more freedom and more access to resources to accomplish goals. You have more comfort as well leading to more happiness. 

*   Health: If you are healthy, you face less day to day struggles, which may put you farther and farther away from happiness. A strong health system promotes happiness because people in general are not worried about sickness creating strain on their life. There is a system in place to accomodate those that have to use the system to maintain normalcy. That said, it has to be a GOOD system that promotes health across the board, and it has to be a system that is easy to access for those who need it.

*   Family: If you have support from your family, you are able to accomplish more. You need to feel safe and supported and not in survival mode. On a larger scale, comfort comes from having a good infrastructure that supports having a family and being able to maintain it. A good economy helps support good health which in turn allows family members to live longer and growing the support system for the individual as a result.

*   Freedom: If you have freedom, you get to choose what you want to do versus being told what to do and how long you have to do it for. The less restricted you are, the more of an architect you are for your own story. Money provides more opportunities and resources for personal happiness but money in the absence of freedom is more frustration in that you are not able to do what you want.

*   Dystopia residual: Not sure about this one. I don't have a good enough understanding of it to properly draw a conclusion on how it ties in to the results. We rather compare ourselves to a less fortunate society than to trust our government or have a generous society to feel better.

*   Trust: Humans are social creatures that strive to build relationships with others. If you live/work in a place with distrust, your ability to build relationships there are stunted.According to Maslow's Hierarchy of Needs, you will need to fill the bottom tiers before moving on to the higher ones, one of which includes personal happiness. In a survivalist mindset, trust doesn't make it to the top 2 factors. If I am paid and healthy at least, I can survive. Just because I can trust people doesn't mean I can get as far as I can with money and health. I also can't trust the government to provide for me if our economy is not in a good state. As a result, trust wouldn't be that much of a factor in my happiness.

*   Generosity: As a humans, we are selfish. We often give to others to make ourselves feel better. As a result, it doesn't appear that generosity has much influence on a country's overall happiness. 
