library(shiny)

# Define UI for application that draws a histogram
shinyUI(fluidPage(

  # Application title
  titlePanel("Histogram!"),

  # Sidebar with a slider input for the number of bins
  sidebarLayout(
    sidebarPanel(
      sliderInput("bins",
                  "Number of bins:",
                  min = 10,
                  max = 100,
                  value = 25),
    
        h2("Histogram"),
        p("A histogram is created when the data is quantitative in nature."),
        h3("Slider"),
        p("A SLIDER is also created above to increase or decrease the number of bins of the histogram. The minimum number of bins allowed is 10 and maximum is 100. The histogram plot is reactive as it re-executes autumatically when the value on the Slider changes ")
        ),
    # Show a plot of the generated distribution
    mainPanel(
      plotOutput("distPlot"),
      p("The histogram displays the data of the second variable of the faithful dataset present in the R software.")
    )
  )
))
