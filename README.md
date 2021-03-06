# Apple-Watch-Health-Data-Analysis
Analyze Health Data from Apple Watch

## Extract data from Apple Watch

Install QS Access App. Details here: http://quantifiedself.com/access-app/app

Run the app, give it access to the health data and extrace activity calories, distance, heartrate, and steps per hour.

## Analysis Environment

I used the IBM Data Science Experience environment to analyse the data. You can register for this environment at http://datascience.ibm.com. It gives access to an RStudio environment and to Jupyter notebooks with Spark underneath.

## Analysis 1

The R Markdown (analyze-health.Rmd) should do all the work. It is best used with RStudio.
My environment is English. If you have a different environment the factors need to be changed.

## Sample execution

You can find a sample execution of the script here: http://hoge-uebler.de/analyse-von-aktivitaetsdaten-der-apple-watch/

## Analysis 2

For this analysis you need the current version of the QS Access App. This version can extrace the complete set of data. Do this for Heart Rate, Steps and Activity Calories.

The R Markdown (analyze-health-detail.Rmd) should do all the work. The most interesting result is how the version of the WatchOS influences heart rate measurement.

More details (in German) here: http://hoge-uebler.de/pulsmessung-der-apple-watch-abhaengig-von-watchos and http://hoge-uebler.de/analyse-der-pulswerte-aus-der-applewatch-mit-r
