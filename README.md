# Coronavirus 2019-nCoV

I made this program just for practice. It uses python and Google Spreadsheets API. I got data from: https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html?fbclid=IwAR3S1IMXpzD-EfOPqWCDttt96vuDQ77Uddrqhhf-iTRmYKxyOPQlPhsxG14#/bda7594740fd40299423467b48e9ecf6, provided by JHU CSSE.

Today (5.02.2020) they changed link to spreadsheet and also added new one with timeseries. Because of that i have to do  some changes in plans for that project.

**Things i plan to do:**
- [x] Open google spreadsheet from url using **oauth2** and **gspread**
- [x] Get data from google spreadsheet with **gspread** and **gspread_dataframe**
- [x] **Clear data** - fillna, drop NaN columns and rows, drop columns I don't need
- [x] **Save** cleared data to excel file (many sheets and one big dataframe to separate file)
- [ ] Standarise data - column names, values in cells
- [ ] **Marge dataframes** from separate worksheets to one big dataframe
- [ ] Change data type in column "Last Update" to **datetime**
- [ ] **Group data by** countries or regions
- [ ] **Plot** data (maybe some interactive plots)