install.packages("readxl")
# Load the readxl library
library(readxl)

# Example - ousourced 
path <- file.path("C:", "Users", "John", "Documents", fsep="\\")
setwd(path)

# Specify the file path
file_path <- file.path("C:", "Users", "kumbalas-INS", "Downloads", "Sim.xlsx")


# Print the file path (optional)
cat("File Path:", file_path, "\n")
C:\Users\kumbalas-INS\Downloads\sim.xlsx

# Load the readxl package to read Excel files
library(readxl)
data <- read_excel(file_path)

# Read the dataset with the filepath 

file_path <- file.path("C:", "Users", "kumbalas-INS", "Downloads", "Sim_2.38134535.xls")
