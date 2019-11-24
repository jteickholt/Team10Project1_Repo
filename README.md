### Team10Project1_Repo
#### Team Members:  Xiaodi Lin, Steve Bark, Jeff Eickholt
#### Project Summary: Analaysis of Texas STAAR math test results for 2019

#### Folders
#### cleandata : Contains data files that were created from the rawdata sources.  Some of these file were the result of pulling multiple data sources together, dropping unnesary data and possibly merging with other files.  These files may be imported in notebooks for various analysis.  Files Include:
1.  AllStudentsGrade3.csv:  Test results for all students grade 3.  Also contains school type and school address.
2.  AllStudentsGrade4.csv:  Test results for all students grade 4.  Also contains school type and school address.
3.  AllStudentsGrade5.csv:  Test results for all students grade 5.  Also contains school type and school address.
4.  DemographicsHABWGrade3.csv:  Test results for all students grade 3 by racial demographic.  Also contains school type and school       address.
5.  DemographicsHABWGrade4.csv:  Test results for all students grade 4 by racial demographic.  Also contains school type and school       address.
6.  DemographicsHABWGrade5.csv:  Test results for all students grade 5 by racial demographic.  Also contains school type and school       address.
8.  EconomicallyDisadvantagedGrade3.csv:  Test results for economially disadacantaged students grade 3.  Also contains school type and school  address.
9.  EconomicallyDisadvantagedGrade4.csv:  Test results for economially disadacantaged students grade 4.  Also contains school type and school address.
10.  EconomicallyDisadvantagedGrade5.csv:  Test results for economially disadacantaged students grade 5.  Also contains school type and school address.
11.  FinalHeaders.csv: File than contains the names of the fields that we chose from the raw school test data.
12.  grade3_geodata.csv:  This contains the test results, school level info, and the latitude and longitude from the Google Geocode API.  Saved to be used in further analysis.
13.  grade3_univdata.csv:  This contains the test results, school level info, latitude and longitude, and result from Google Place API on proximity to universtity.  Saved to be used in further analysis.

#### libraries:  Folder to contain any needed libraries.  This was not used.

#### notebooks:  Contains all notebooks used in analysis.  Files Include:
1.  AllStudentsCalcs.ipynb:  Analysis for all students for all grades.  Author:Steve
2.  DemographicsCalcs.ipynb:  Analysis based on racial demographics for all grades. Author:Steve
3.  ED+Calcs.ipynb:  Analysis for economically disadvantaged students for all grades. Author:Steve
4.  SchoolData_Focused_Grade3.ipynb:  Processing raw data create AllStudentsGrade3.csv.  Author:Steve
5.  SchoolData_Focused_Grade4.ipynb:  Processing raw data create AllStudentsGrade5.csv. Author:Steve
6.  SchoolData_Focused_Grade6.ipynb:  Processing raw data create AllStudentsGrade6.csv. Author:Steve
7.  jeff.ipynb:  Analyis geographical relationship. Authoer:  Jeff

#### rawdata:  Contains all of the raw data files.

#### reports:  Contains reports and charts
