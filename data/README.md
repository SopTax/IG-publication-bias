# Data Access

This repository does not include study data.
- **FDA data:** please supply the Excel file referenced in the notebook at `pathFDA`, which is found in this folder as FDA_data
- **In-house data:** not publicly shareable. If you have access, place the file locally and set `pathInHouse` in the Rmd. 

The data needs to have the following structure: 
- One column called _ymax_ which represents ADA positivity rate, and
- one column with compound names called _ID_.
  
The notebook is written so paths can be edited at the top, and steps for formatting are explained throughout the notebook. 
