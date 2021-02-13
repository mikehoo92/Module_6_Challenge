# Proptech - San Francisco
## *Buy & Sell?* No, Buy & Rent!

This notebook offers analystss at a Proptech company to test a service that offers an instant, one click service for investors to buy properties and then rent them. To do this, we will use data visualizations, including aggregation, interactive visualizations, and geospatial analysis to find properties in the San Francisco Market that are viable investment opportunities.

![](Images/mapbox-plot.png)

---

## Technologies

This project uses a Jupyter Notebook in Jupyter Lab with the following libraries:

- Pandas: to help with the robust amount of features that will help analyze and organize the data.
- pathlib: to extract the data from the CSV file using the file path.
- Plotly Express: to create interactive maps for our geospatial data
- PyViz & hvPlot: to create interactive data visualizations
- dotenv and os: to access our Mapbox API Access Token variable from the .env file and read in the Mapbox API Key.


---

## Usage

To succesfully run this notebook, please be sure to import the required libraries and dependencies:

```
import os
import pandas as pd
import plotly.express as px
import hvplot.pandas
from pathlib import Path
from dotenv import load_dotenv
```

---

## Contributors

Michael Husary was the main contributer along with fellow classmates and the educational staff. 

--- 

## License
*(Not sure if a license was required on this Challenge)*


MIT
