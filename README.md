# Serie climatica tandil 
dat <- read.csv("https://raw.githubusercontent.com/juanchiem/agro_data/master/tandil_serie71-20.csv", sep = ",")
dat$date <- as.Date(dat$date, format =  "%Y-%m-%d")


