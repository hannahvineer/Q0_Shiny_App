# Q0_Shiny_App

To run the RShiny app, open R Studio and execute the following lines of code:

(Note: you may need to install the shiny, geosphere and forecast packages first).


## To run from a public GitHub repository

library(shiny)

library(geosphere)

library(forecast)

runUrl("https://github.com/hannahvineer/Q0_Shiny_App/Q0_UI.zip")

## To run from a local .zip file - extract the contents of the zip file first

library(shiny)

library(geosphere)

library(forecast)

runApp("~/Q0_UI")
