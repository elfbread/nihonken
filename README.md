# 県の日本　Personalized travel history by Japanese Prefecture

Python and Tableau project to display travel history while living in Japan (2022 - present). 

Data Source: [Japan - Subnational Administrative Boundaries](https://data.humdata.org/dataset/cod-ab-jpn?) - The Humanitarian Data Exchange, OCHA Regional Office for Asia and the Pacific (ROAP)

This project includes data (description). The project does the following: scrapes the web to pull in data table of Japanese prefectures; modifies and drops columns from the scraped data; uses a (something) to assign values to a new column (visit history); exports the final table to .csv for ease of import into Tableau.

After the data is scraped, cleaned and exported, the dataset is imported into Tableau Public. The final project is available [here] (https://public.tableau.com/app/profile/elfbread/viz/VisitedPrefecturesofJapan/Sheet2).

## Start-up instructions

Before starting, you need to download/install the following extensions in VS Code for Jupyter Notebook:

![Juypter Notebook](https://github.com/elfbread/pyAirports/blob/main/extension.png)

Clone the repo to your computer. 

Package requirements are listed in the requirements.txt file. Install the libraries in the requirements.txt file using the following command:

`pip install -r requirements.txt`

Packages used in this project include:

- numpy
- pandas

Create and activate your virtual environment utilizing Command Prompt (more information available here: [venv set up and activation](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/). Be sure to cd into your correct directory prior to setting up and activating your venv!

To create venv:

`python -m venv env`

To activate venv:

`env/Scripts/activate.bat`
 
Navigate to the folder and open main.ipynb with VS Code. Be sure to update the kernel in the upper right of VS Code (as shown in the screenshot below).The file imports uses public CSVs saved in my Google Sheets account, a work around for users utilizing different operating systems (not having to adjust the import statement/file path).

![Juypter Notebook](https://github.com/elfbread/pyAirports/raw/main/kernel.png)
