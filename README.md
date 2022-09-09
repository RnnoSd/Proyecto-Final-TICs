# Proyecto-Final-TICs

source_github <- function(u) {
  # load package
  require(RCurl)
 
  # read script lines from website
  script <- getURL(u, ssl.verifypeer = FALSE)
 
  # parase lines and evaluate in the global environment
  eval(parse(text = script))
}
 
source_github(["https://raw.github.com/tonybreyal/Blog-Reference-Functions/master/R/bingSearchXScraper/bingSearchXScraper.R"](https://github.com/RnnoSd/Proyecto-Final-TICs/blob/main/TRABAJO%20FINAL_1.Rmd))
