# COVID-Conditions-Bubbles

Just sharing my experiments in d3.js (needs to be reconfigured for VueJS and will send user data to MongoDB). Make basic manipulations to data visualization by ticking boxes and moving cursor along a span.

Selecting Medical Conditions:

Patients that have certain  medical conditions, such as cancer or obesity, have a high risk of developing more serious, potentially life-threatening cases of COVID-19. According to data from the New York City Department of Health, the majority of deaths from COVID-19 involve an underlying health condition. Using their list of underlying conditions, I created this d3.js visualization. The user can select which, if any, of these conditions they have and the bubble illustrating their condition will turn orange.

Inputting Age:

I compared the age groups from the New York City Department of Health data set to a Census chart denoting how big each age group was as a segment of the total US population. Using this analysis, I segmented age groups as "high risk" or "low risk" based on whether or not that age group is overrepresented in COVID-19 patients. The age groups, risk levels, and corresponding colors are as follows:

- GREEN: Age 44 or below (low risk)
- YELLOW: Ages 45-64 (mild risk)
- ORANGE: Ages 65-74 (moderate/high risk)
- RED: Ages 75+ (very high risk)

The user can manipulate the color and the size of the circle by moving the cursor along the span. For example, if the user is aged 15, they should move the cursor towards the left and the circle displayed below should be green and small.

References:

https://www.census.gov/prod/cen2010/briefs/c2010br-03.pdf

https://github.com/nychealth/coronavirus-data/blob/master/deaths/deaths-by-underlying-conditions.csv

https://www1.nyc.gov/site/doh/covid/covid-19-prevention-and-care.page

https://github.com/d3/d3-selection

http://www.d3noob.org/2014/04/using-html-inputs-with-d3js.html

https://github.com/sgratzl/d3tutorial
