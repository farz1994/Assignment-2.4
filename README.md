1. x <- c(‘data.science.in.R’, ‘machine.learning.in.R’)
Perform the below string Operation:
• Replace the period character "." within each string with another character i.e. "-" minus sign.
x <- c("data.science.in.R", "machine.learning.in.R")
gsub(".", "-", x, fixed = TRUE)
> gsub(".", "-", x, fixed = TRUE)
[1] "data-science-in-R"     "machine-learning-in-R"

2. x <- c('data.science.in.R','machine.learning.in.R')
Perform the below String Operation:
• Append again with “-“ minus sign character at the start of the each string and finally concatenate all the
string within the vector to form a final single string and assigning it the object.

x <-paste0("-",x, collapse = "")
[1] "-data-science-in-R-machine-learning-in-R"

