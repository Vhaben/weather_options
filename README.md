# Pricing temperature options in New York City

> CapitOx Quantitative Strategies Academy Final Project

## About

After being selected to join CapitOx &mdash; Oxford's premier finance and consulting society &mdash;, I completed their Quantitative Strategies Academy, which culminated in a group project.  
My other two teammembers and I chose to focus on the weather derivatives market, and, in particular, on pricing such options in New York City.

## Motivation

We were drawn to this topic because of its subtle but increasingly monumental importance.

It's estimated that nearly one-third of the world's GDP is affected by the climate.

### History

Weather derivatives are seeing greater use to hedge against deleterious weather conditions.  
But the market has existed for longer than one might expect.

It emerged OTC in July 1996 and become established when the Chicago Mercangile Exchange (the CME) introducted exchange traded weather futures and options in 1999.

Traded volumes do remain small but many forecast substantial growth.

## Principles

These options are typically structured based on the number of Degree Days (DD), in which the mean temperature (defined as the average of the max and min on a given day) is above or below a certain reference (typically 18 &deg;C).  
The expected payoff of an option is simply a function of the number of DD in a given period, relative to the strike level (a predetermined number of DD).

Businesses not only often treat these contracts as insurance, but also choose to write these optinos themselves.  
For example, a heating oil retailer expecting a very cold winter, and therefore high revenues, might sell an HDD call.  
If the winter is not cold, the heating oil retailer keeps the premium on the call. If it is, the strong season can compensate for the loss.

As the underlying variable, the temperature, is not tradable, the weather derivatives market is incomplete.

## Process

We divided the work as follows:
- Data sourcing: finding historical weather data and options prices
- Coding: data cleaning, researching methods used, and implementation
- Presentation and viability: creating the PowerPoint presentation and comparing the results of the code with the historical market

I was responsible for coding so I can only speak in detail to that facet.  
The work mostly involved finding papers on the topic, and implementing the methods presented in Python.

As this was our first quant project, we had to draw from many [very helpful sources](#references).  
My goal was to digest the content, implement it efficiently, and add my own spin.  
I used models with which I was more familiar, and chose some of the more approachable methods I could find.

## References

A non-exhaustive list of helpful resources:
- Esunge, J., & Njong, J. J. (2020). Weather derivatives and the market price of risk. Journal of Stochastic Analysis, 1(3), 7.
- Mraoua, M. (2007). Temperature stochastic modeling and weather derivatives pricing: empirical study with Moroccan data. Afrika Statistika, 2(1).
- Tindall, J. (2006). Weather derivatives: pricing and risk management applications. Institute of Actuaries of Australia.
- Considine, G. (2000). Introduction to weather derivatives. Weather derivatives group, Aquila energy, 1-10.
- QuantPy Pty Ltd (2022). Monte Carlo Simulation of Temperature for Weather Derivative Pricing.
- Bemš, J., & Aydin, C. (2022). Introduction to weather derivatives. Wiley Interdisciplinary Reviews: Energy and Environment, 11(3), e426.
- Wang, Z., Li, P., Li, L., Huang, C., & Liu, M. (2015). Modeling and forecasting average temperature for weather derivative pricing. Advances in Meteorology, 2015(1), 837293.

## License

All files associated with this porject formed part of the CapitOx Quantitative Strategies Academy. All content presented in these files is intended for informational and educational purposes for the fund only and should not be considered as investment advice. The content has been assembled through publicly available information. No responsibility is assumed for the accuracy of the information used within this document and do not assume any liability for it.
