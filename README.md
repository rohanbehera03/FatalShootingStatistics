# final-project-cs166veterans
Our project explored a selected dataset that covered fatal police shootings data in the US. 
This dataset includes victim information such as name, age, gender, and threat_type. There are multiple types of threats indicated including shooting a weapon, pointing a weapon at someone else, attacking someone with their weapon or with physical force, making their weapon visible to officers, etc. 
There is also incident information such as date, city, county, state, whether there was a body camera worn by the officer, latitude, longitude, and location precision.
We wanted to observe how select variables could determine or predict a fatal police shooting.
We did this through the creation of data models. 
Our project focused on using decision trees and a random forest algorithm as predictors. 
Various decision trees used various input variables to predict a location that the fatal shooting would take. 
The random forest algorithm focused on predicting the latitude and longitude.

Source of dataset: https://github.com/washingtonpost/data-police-shootings/tree/master/v2

--
Our project is formatted as a jupyter notebook. \
To run our Jupyter Notebook, download the contents of this repo as a ZIP file and upload cs108project_final.ipynb into your JupyterLab account. Then click on Run in the menu bar and click on Restart Kernel and Run All Cells...
The various libraries that we used can be downloaded by running the following:\
If running on JupyterLab use !/opt/anaconda/bin/pip \
Otherwise !pip install

!/opt/anaconda/bin/pip install --upgrade pip install \
!/opt/anaconda/bin/pip install numpy \
!/opt/anaconda/bin/pip install pandas \
!/opt/anaconda/bin/pip install seaborn \
!/opt/anaconda/bin/pip install matplotlib \
!/opt/anaconda/bin/pip install scipy \
!/opt/anaconda/bin/pip install plotly \
!/opt/anaconda/bin/pip install scikit-learn==0.22.2 \
!/opt/anaconda/bin/pip install plotly==5.13.1 

This portion of code will also be on the top of our final jupyter notebook to make it easier for others to run it. 

--
Presentation Slides: https://docs.google.com/presentation/d/1pZ7QEjDNx_xCZ9O6DYLJxNBgCPpHLs6H/edit?usp=sharing&ouid=108505867221132463731&rtpof=true&sd=true
