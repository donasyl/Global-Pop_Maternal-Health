Global Population Growth and Maternal Health Analysis

Author: Donasyl Marie Aho
Project Type: Exploratory Data Analysis | Demography | Global Health
Tools: Python, NumPy, datascience, Matplotlib
Data Source: Gapminder (Systema Globalis)

Project Overview

This project explores global population trends and maternal health indicators using publicly available data from Gapminder. The analysis focuses on how population growth relates to life expectancy, fertility rates, and child mortality, with a detailed case study of Bangladesh from 1970 to 2015.

By combining demographic data with health indicators, this project demonstrates how population dynamics are closely linked to improvements in public health, particularly maternal and child outcomes.

Research Questions

How has global population growth changed across regions over time?

What demographic trends explain changes in population growth rates?

How are fertility rates and child mortality related?

How do maternal and child health improvements influence long-term population patterns?

Data Description

All datasets originate from Gapminder’s Systema Globalis, which compiles international public statistics.

Key Tables Used

population.csv: Population counts by country and year

country_regions.csv: Country names, ISO alpha-3 codes, and regions

life_expectancy.csv: Life expectancy at birth

fertility.csv: Total fertility rate (children per woman)

child_mortality.csv: Child mortality per 1,000 births

Each dataset includes:

Country code (geo)

Year (time)

A numerical demographic or health indicator

Data Preparation

Filtered population data to the years 1970–2015

Joined country-level population data with regional classifications

Aggregated population totals by region and year

Isolated Bangladesh for focused longitudinal analysis

Aligned fertility and child mortality data by year using table joins

Global Population Analysis

Using regional aggregation, population growth trends were visualized for:

Africa

Asia

Europe

Americas

Oceania

The analysis shows rapid population growth in Asia and Africa, with slower growth in Europe and the Americas. These trends align with differences in fertility rates and health outcomes across regions.

Case Study: Bangladesh

Bangladesh was selected to explore how health indicators influence population growth over time.

Population Trends

Population steadily increased from 1970 onward

Growth rate slowed significantly between the mid-1980s and early 2000s

Life Expectancy

Life expectancy increased substantially over time

A noticeable drop occurred in 1991, corresponding to the Bangladesh cyclone that caused significant loss of life

Fertility and Child Mortality Analysis

To understand changes in population growth, fertility rates were examined alongside child mortality.

Fertility rates declined sharply over time

Child mortality rates dropped substantially

A strong inverse relationship was observed between fertility and child mortality

This relationship supports the theory that when child survival improves, families tend to have fewer children.

Key Findings

Global population growth varies significantly by region

Improvements in child survival are closely associated with declining fertility

Public health improvements play a major role in shaping demographic transitions

Bangladesh demonstrates how reductions in child mortality contribute to slower, more stable population growth

Visualizations Created

Regional population growth over time

Bangladesh population trends

Life expectancy trends for Bangladesh

Scatter plot of fertility vs. child mortality for Bangladesh

All visualizations were generated using Matplotlib and the datascience plotting utilities.

Limitations

Analysis focuses on a limited time range (1970–2015)

Does not account for migration or policy interventions

Country-level data may mask subnational variation

Observational data limits causal inference

Conclusion

This project illustrates how demographic and health data can be combined to explain population trends at both global and country levels. The strong relationship between fertility and child mortality highlights the importance of maternal and child health interventions in shaping long-term population outcomes.

Understanding these patterns is essential for policymakers, global health professionals, and researchers planning for sustainable development in the 21st century.
