<img title="covid task" alt="covid" width="1000" height="250" src="https://fv9-4.failiem.lv/thumb_show.php?i=kcw6tbqzk&view" />

## Covid 19 Task 

## Introduction:

The goal of this task was to make a covid 19 analysis,train a predictive model to present 
the situation through the next year(without measures against COVID-19 ) and finally
produce an automated one-page report (word document) for each country

## Process:

- The analysis was focused on how composite measure based on 9 response indicators including school closures, workplace closures, and travel bans(Stringency Index)
  had an impact in battle against covid 19.
  
- Time series was used for the prediction of future covid cases

- Word automated report with python's docx
  

## Results:

In the analysis folder there are four graphs about average strindency index per year,correlation between strindency_index and cases/deaths and finally
an exploration of how countries healthcare systems associated with stricter measures

The predictive model could not make accurate predictions for next years situation as covid is a virus that came into our lives only two years ago.
Also the seasonality of the data is very bad (key factors are measures taken and omicron variant).However in some hypothetical data prothet model was
able to produce some decent results

The one page report was accomplished by creating a script that takes users input (country) and produces a word document containing a table and a graph
for selected country's total cases/population

## Repository contents:
- Analysis
- Cleaning
- Model
- Word Automation
- Environment

## Related links:
The reason china was excluded from the analysis <a href="https://en.wikipedia.org/wiki/COVID-19_misinformation_by_China">Link</a>

Covid in africa was less deadly (scatter plot outlier) <a href="https://gdc.unicef.org/resource/coronavirus-africa-five-reasons-why-covid-19-has-been-less-deadly-elsewhere">Link</a>

