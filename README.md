# Template Shiny App in R

Server-side Shiny app example in R hosted on ShinyApps:

<https://jobs-george.shinyapps.io/template-shiny-r/>

# Getting Started

Run the app locally by:

1.  Restoring the dependencies with `renv::restore()`

2.  Running the app with `shiny::runApp()`

# Deployment

Use the following steps to deploy the app:

1.  Install the `rsconnect` package (`renv::install("rsconnect")`)

2.  Create a ShinyApp.IO account and token

3.  Set the fields of `rsconnect::setAccountInfo()`

4.  Deploy the app with `rsconnect::deployApp()`

# Contribute

N/A
