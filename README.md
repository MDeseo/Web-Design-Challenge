## Assignment 11 - Web-Design-Challenge

HTML and CSS were used to create a dashboard featuring the Latitude vs. X analysis of weather from the data provided that are in the "Resources" folder.
The html files were created in Visual Studio Code version 1.72.1.


The local Git repository contains the following:

- This "README" file.

- "index.html" file, which is the main landing page for the website.

- "Resources" folder that contain all the provided data: "cities.csv" file containing the data for the website, and a folder "assets" that contains the "images" folder with the four plot figures that were used on the website.

- "assets' folder that contains two sub folders: "css" folder that contains the css "style" file, and "images" folder that contains the screenshot images of the website created.

- "visualisations" folder that contains four visualisation landing pages that links to the main landing page ("index.html").

- "Comparison" landing page that is linked to the main landing page ("index.html")

- "csv to html" jupyter file that was the result of converting "cities.csv" file to html file using Pandas "to_html" method that generates an HTML table from a Pandas DataFrame. This file was created in conda version 4.13.0 in "PythonData" environment using Jupyter Notebook.

- "Data" landing page that displays a responsive table containing the data that the visualisations use.


The website creation took into consideration building a dashboard using Bootstrap navbar component for the header on every page, the Bootstrap grid for responsiveness on the comparison page, and the Bootstrap table component for the data page.

A CSS media query that uses Bootstrap and/or @media for the navigation bar was used and the website was created to work at all window widths.

The website consists of seven pages and at the top of every page, the website has an interactive navigation bar that can take the viewer to any page on the website without clicking the return arrow on the browser.

The main landing page ("index.html") provides an explanation of the project and links to each visualisation page though a preview image of each visualisation. Clicking an image takes the viewer to that visualisation.

As the dashboard in "index.html" is built, a page for each plot in the button "Plots" was created and linked in the navigation bar to navigate among the visualisation pages. These pages contain the visualisations, descriptions, descriptive title and heading tag. The visualisation for the selected comparison includes city latitude vs. max temperature, city latitude vs. humidity, city latitude vs. cloudiness, and city latitude vs. wind speed).

Two more buttons were created for the comparison page that compares the four plots, and for the data page that presents the data used to build the plots. The comparison page contains all the visualisations on the same page so that viewers can easily compare them. Clicking on any image takes the viewer to its corresponding page. 

The data page displays a responsive table containing the data that the visualisations use and has Bootstrap table component. The data came from converting the "citis.csv" file to "cities.html" file. This was done by using Pandas tool "to_html" method that generates an HTML table from a Pandas DataFrame. The file was created in Jupyter notebook and file name is "csv_to_html.ipynb". The generated file, "cities.html", was later saved as "Data.html".

The website was deployed to GitHub Pages, and as a result, the website works at a live, publicly accessible URL.

The screenshot of all the pages displayed are stored in the "assets/images" folder.

