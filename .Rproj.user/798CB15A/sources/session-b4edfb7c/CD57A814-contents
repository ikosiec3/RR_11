library(tidyverse)
library(pastecs)


students <- data.frame(
  Name = c("Anna", "John", "Kate", "Mike", "Emma"),
  Score = c(78, 85, 92, 88, 95),
  Hours_Studied = c(4, 5, 7, 6, 8)
)


print(students)


stats <- stat.desc(students[, c("Score", "Hours_Studied")])

print(stats)

ggplot(students, aes(x = Hours_Studied, y = Score)) +
  geom_point(size = 3) +
  geom_smooth(method = "lm", se = FALSE) +
  ggtitle("Study Hours vs Exam Score")
