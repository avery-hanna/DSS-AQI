# DSS-Asthma
Predict asthma-related hospital visits by AQI in California

Code: 
All code is done in the aqi_prediction.ipynb file

Data sources:
- Air quality data from https://www.epa.gov/outdoor-air-quality-data/download-daily-data 
- Asthma ED visit data from https://data.ca.gov/dataset/asthma-emergency-department-visit-rates/resource/ebc3ac2f-5b39-4db3-90aa-55e69612d78c 
- Meteorology data from http://www.cimis.water.ca.gov/ 
- Poverty data from https://hdpulse.nimhd.nih.gov/data-portal/social/table?age=001&age_options=ageall_1&demo=00007&demo_options=poverty_3&race=00&race_options=race_7&sex=0&sex_options=sexboth_1&socialtopic=080&socialtopic_options=social_6&statefips=06&statefips_options=area_states 
- Health insurance data from https://hdpulse.nimhd.nih.gov/data-portal/social/table?age=001&age_options=ageall_1&demo=00007&demo_options=poverty_3&race=00&race_options=race_7&sex=0&sex_options=sexboth_1&socialtopic=080&socialtopic_options=social_6&statefips=06&statefips_options=area_states
- Census (ethnicity) data from https://dof.ca.gov/reports/demographic-reports/american-community-survey/#ACS2017x5 



Using Git:

set up:
1. Clone repo to your computer so you'll be able to work locally: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

Work flow:
1. git pull: updates your local code with any changes that have been added
2. git checkout -b your-branch-name: make a new branch named your-branch-name. Takes you to that branch
3. git checkout your-branch-name: takes you to a branch that has already been made
4. git add . : adds all the changes you have made so you can commit them
5. git commit -m "your message here": commits your changes logging the updates you've made on your branch. Still local
6. git push: updates the github with the changes you committed. Now everyone can see the work you did on your branch
