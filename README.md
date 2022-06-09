<img title="covid task" alt="covid" width="1000" height="250" src="https://fv9-4.failiem.lv/thumb_show.php?i=kcw6tbqzk&view" />

# Covid 19 Task 
Submitted by: Sekis Stefanos 

Date: 09/06/2022

## Introduction:

The goal of this task was to make a covid 19 analysis,train a predictive model to present 
the situation through the next year(without measures and vaccinations against COVID-19 ) and finally
produce an automated one-page report (word document) for each country

## Process:

- The analysis was focused on how composite measure based on 9 response indicators including school closures, workplace closures, and travel bans(Stringency Index)
  had an impact in battle against covid 19.
  
- Time series models were used for the prediction of future covid cases

- Automated word report with python's docx
  

## Results:

In the analysis folder there are four graphs about average strindency index per year,correlation between strindency_index and cases/deaths and finally
an exploration of how countries healthcare systems associated with stricter measures

The predictive models could not make accurate predictions for next years situation as covid is a virus that came into our lives only two years ago.
Also the seasonality of the data is very bad (key factors are measures taken and omicron variant).However in some hypothetical data 
(2021,not included omicron variant) prothet model was able to produce some decent results which you can see in the second attempt in the models notebook.Models were tested on total worldwide cases per day

The one page report was accomplished by creating a script that takes users input (country) and produces a word document containing a table and a bar chart
for selected country's total cases/population.The script must be in the same folder with the adjusted dataframe(cases_population) in order to run

## Repository contents:
:bar_chart: Analysis

:broom: Cleaning

<img title="data" alt="data" width="18" height="18" src="https://cdn.icon-icons.com/icons2/2566/PNG/512/data_icon_153327.png" />  Data 

<img title="time series" alt="model" width="18" height="18" src="https://cdn-icons-png.flaticon.com/512/6361/6361000.png" />  Models

<img title="word report" alt="word report" width="18" height="18" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/.docx_icon.svg/1200px-.docx_icon.svg.png" />  Word Automation

<img title="env" alt="virtualenv" width="18" height="18" src="https://cdn.tutsplus.com/cdn-cgi/image/width=300/net/uploads/2013/05/python-power-400.jpg" />  Environment

## Related links:
The reason china was excluded from the analysis: <a href="https://en.wikipedia.org/wiki/COVID-19_misinformation_by_China">Link</a>

Covid in africa was less deadly (scatter plot outlier): <a href="https://gdc.unicef.org/resource/coronavirus-africa-five-reasons-why-covid-19-has-been-less-deadly-elsewhere">Link</a>

Original dataset: [Data on COVID-19 (coronavirus) by Our World in Data](https://github.com/owid/covid-19-data/tree/master/public/data)
