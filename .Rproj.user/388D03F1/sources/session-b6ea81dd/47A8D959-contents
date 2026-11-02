
# STAT 301-1 Final Project
# Heart Disease Mortality EDA

# Load required packages
library(tidyverse)

# Import CDC Heart Disease Mortality Data
heart_data <- read_csv(
  "https://data.cdc.gov/api/views/mri7-5jtw/rows.csv?accessType=DOWNLOAD"
)

# View the dataset
View(heart_data)

# Check the number of rows and columns
dim(heart_data)

# Examine the variables
glimpse(heart_data)

# Check for missing values
colSums(is.na(heart_data))
