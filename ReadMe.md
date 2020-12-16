### Overview
This repo is for programs that communicate with the Peloton API to get detailed workout statistics for a desired user.</br>
As of right now there is only the python version in jupyter notebook, a Javascript version will be added at some point as well.

### Python Version 
Most of the API fetching is pulled Directly from here: https://github.com/davidvelleca/PelotonAPI/blob/master/peloton_py.py </br>
Slight modifications are made to use the data in dataframe form rather than exporting to a CSV </br>
Still a work in progress and will be expanded upon in the future </br>
The program is split up into multiple cells that can be run separately </br>
# Cell 1
Imports all required libraries. </br>
Must be run first but only needs to be run once
# Cell 2 
Requests the users login info.</br>
Must be run second and does not need to run again unless searching another user.<br/>
Will return 200 if the user exists, if anything else is returned run this cell over again with correct info
# Cell 3 
The bulk of the API calls take place here. </br>
Must be run immidiately after cell 2 is run every time
# Cell 4+
Everything after cell 3 is optional and provides a different set of statistics and graphs
Read the commented description for its purpose and run if you are interested in that data </br>
