![GIF 2021-01-02 20-55-14](https://user-images.githubusercontent.com/63854101/103456826-21c78600-4d3d-11eb-86b1-b2fdf1fdb4e2.gif)

## COVID-19 Dashboard in Japan
COVID-19 Dashboard in Japan, powered by Shiny web app, demonstrates interactive plots and summary to figure out how COVID-19 had spread throughout Japan. 
The dataset is retrieved from [COVID-19 dataset in Japan in Kaggle](https://www.kaggle.com/lisphilar/covid19-dataset-in-japan)

## General Info
Like other nations, Japan has been struggling with an unprecedented battle with the infectious disease since Feb 2020. The news media broadcasts daunting reports/figures from various perspectives daily. Think for a moment, should we take them at face value? Are there missing parts from their perspective? That is the main motivation which drove me to develop this web application.By leveraging the public dataset, this Shiny-powered web application helps even non-experts intuitively understand how we are affected by COVID-19 from the different aspects not shown by the news media.  

## Demo
Here is a working live demo: https://mhirono1351.shinyapps.io/covid19_dashboard/

## Features
* Reactive data filters of date, the breakdown of testing, and types of hospitals
* 4 panels of the summary including the total testing, positive cases, death, and out-hospital
* 2 event-driven interactive plots of the positive cases per hospital bed, and transition of the prevalence rate

## Technologies
The dashboard is created by R (4.0.3) with the following relevant packages:
* chorophlethr (3.7.0)
* chorophlethrAdmin1 (1.1.1)
* flexdashboard (0.5.2)
* plotly (4.9.2.1)
* shiny (1.5.0)
* shinyjs (2.0.0)
* shinyWidgets (0.5.4)
* tidyquant (1.0.2)
* tidyverse (1.3.0)

## Development
Your contribution would be much appreciated. 
To fix a bug or enhance an existing module, follow these steps:

* Fork the repo
* Create a new branch (`git checkout -b improve-feature`)
* Make the appropriate changes in the files
* Add changes to reflect the changes made 
* Commit your changes (`git commit -am 'Improve feature'`)
* Push to the branch (`git push origin improve-feature`)
* Create a Pull Request

## Bug / Feature Request
If you find a bug or would like to request a new function, feel free to do so by opening an issue [here](https://github.com/mhirono1351/covid19_dashboard/issues/new)

## Author
* Name: Masatake Hirono
* Organization: Deloitte Tohmatsu Consulting
* E-mail: masatakehirono1351@gmail.com
