# Given vector
my_vector <- c(1, 2, 3, 4, 5)

# Reverse the order
reversed_vector <- rev(my_vector)

# Print the result
cat("Original Vector:", my_vector, "\n")
cat("Reversed Vector:", reversed_vector, "\n")
# Given vectors
vector1 <- c(1, 2, 3)
vector2 <- c(4, 5, 6)

# Concatenate vectors
concatenated_vector <- c(vector1, vector2)

# Print the result
cat("Vector 1:", vector1, "\n")
cat("Vector 2:", vector2, "\n")
cat("Concatenated Vector:", concatenated_vector, "\n")
# Given vector
my_vector <- c(5, 10, 15, 20, 25, 30)

# Count values in the range (10, 20)
count_in_range <- sum(my_vector > 10 & my_vector < 20)

# Print the result
cat("Vector:", my_vector, "\n")
cat("Count in Range (10, 20):", count_in_range, "\n")
# Given vectors
vector1 <- c(1, 2, 3)
vector2 <- c(4, 5, 6)

# Combine by row
combined_by_row <- rbind(vector1, vector2)

# Combine by column
combined_by_col <- cbind(vector1, vector2)

# Print the results
cat("Combined by Row:\n", combined_by_row, "\n")
cat("Combined by Column:\n", combined_by_col, "\n")
# Given vectors
vector1 <- c(1, 2, 3)
vector2 <- c(4, 5, 6)

# Combine by row
combined_by_row <- rbind(vector1, vector2)

# Combine by column
combined_by_col <- cbind(vector1, vector2)

# Print the results
cat("Combined by Row:\n", combined_by_row, "\n")
cat("Combined by Column:\n", combined_by_col, "\n")
# Given vector
my_vector <- c(5, 12, 8, 15, 20)

# Test condition
greater_than_10 <- my_vector > 10

# Print the result
cat("Vector:", my_vector, "\n")
cat("Values Greater than 10:", greater_than_10, "\n")
# Create a list
my_list <- list("Hello", 123, c(1, 2, 3), TRUE)

# Print the result
cat("List:", my_list, "\n")
# Create a list
my_list <- list(
  my_vector = c(1, 2, 3),
  my_matrix = matrix(1:4, nrow = 2),
  my_nested_list = list("A", "B", "C")
)

# Access elements
first_element <- my_list[[1]]
second_element <- my_list[[2]]

# Print the result
cat("List:", my_list, "\n")
cat("First Element:", first_element, "\n")
cat("Second Element:\n", second_element, "\n")
# Create a list
my_list <- list(
  my_vector = c(1, 2, 3),
  my_matrix = matrix(1:4, nrow = 2),
  my_nested_list = list("A", "B", "C")
)

# Add an element
my_list$additional_element <- "New Element"

# Print the result
cat("Updated List:\n", my_list, "\n")
# Given nested list
nested_list <- list(c(1, 2, 3), c("A", "B", "C"), list(TRUE, FALSE))

# Select the second element
second_element <- nested_list[[2]]

# Print the result
cat("Nested List:\n", nested_list, "\n")
cat("Second Element:", second_element, "\n")
# Given list of vectors
vector1 <- c(1, 2, 3)
vector2 <- c(4, 5, 6)

# Create a matrix
my_matrix <- matrix(c(vector1, vector2), nrow = 2, byrow = TRUE)

# Print the result
cat("Matrix:\n", my_matrix, "\n")
# Given matrix
my_matrix <- matrix(1:9, nrow = 3)

# Extract submatrix
submatrix <- my_matrix[my_matrix[, 1] > 7, ]

# Print the result
cat("Original Matrix:\n", my_matrix, "\n")
cat("Submatrix:\n", submatrix, "\n")
# Given matrix
my_matrix <- matrix(1:9, nrow = 3)

# Convert to a 1-dimensional array
my_array <- as.vector(my_matrix)

# Print the result
cat("Matrix:\n", my_matrix, "\n")
cat("1-dimensional Array:", my_array, "\n")
# Given matrix
my_matrix <- matrix(1:9, nrow = 3)

# Find indices of max and min values
max_index <- which(my_matrix == max(my_matrix), arr.ind = TRUE)
min_index <- which(my_matrix == min(my_matrix), arr.ind = TRUE)

# Print the result
cat("Matrix:\n", my_matrix, "\n")
cat("Index of Max Value:", max_index, "\n")
cat("Index of Min Value:", min_index, "\n")
# Given vectors
vector1 <- c(1, 2, 3, 4, 5, 6, 7, 8, 9)
vector2 <- c(9, 8, 7, 6, 5, 4, 3, 2, 1)

# Create an array
my_array <- array(c(vector1, vector2), dim = c(3, 3, 2))

# Print the result
cat("Array:\n", my_array, "\n")
# Create a 3-dimensional array
my_array <- array(1:24, dim = c(2, 3, 4))

# Print the result
cat("3-dimensional Array:\n", my_array, "\n")
# Given vectors
vector1 <- c(1, 2, 3, 4, 5, 6, 7, 8, 9)
vector2 <- c(9, 8, 7, 6, 5, 4, 3, 2, 1)

# Create an array
my_array <- array(c(vector1, vector2), dim = c(3, 3, 2))

# Access elements
second_row_second_matrix <- my_array[2, , 2]
element_3_3_first_matrix <- my_array[3, 3, 1]

# Print the results
cat("Array:\n", my_array, "\n")
cat("Second Row of Second Matrix:", second_row_second_matrix, "\n")
cat("Element at 3rd Row, 3rd Column of 1st Matrix:", element_3_3_first_matrix, "\n")
# Given arrays
array1 <- array(1:3, dim = c(1, 3))
array2 <- array(4:6, dim = c(1, 3))
array3 <- array(7:9, dim = c(1, 3))

# Combine row-wise
combined_array <- rbind(array1, array2, array3)

# Print the result
cat("Combined Array:\n", combined_array, "\n")
# Given vectors
name <- c("Alice", "Bob", "Charlie")
age <- c(25, 30, 22)
weight <- c(65, 70, 68)
height <- c(170, 175, 160)

# Create a data frame
my_data_frame <- data.frame(Name = name, Age = age, Weight = weight, Height = height)

# Print the result
cat("Data Frame:\n", my_data_frame, "\n")
# Given data frame
my_data_frame <- data.frame(
  Name = c("Alice", "Bob", "Charlie"),
  Age = c(25, 30, 22),
  Weight = c(65, 70, 68),
  Height = c(170, 175, 160)
)

# Statistical summary
summary_stats <- summary(my_data_frame)

# Nature of the data
data_structure <- str(my_data_frame)

# Print the results
cat("Data Frame:\n", my_data_frame, "\n")
cat("Summary Stats:\n", summary_stats, "\n")
cat("Data Structure:\n", data_structure, "\n")
# Given data frame
my_data_frame <- data.frame(
  Name = c("Alice", "Bob", "Charlie"),
  Age = c(25, 30, 22),
  Weight = c(65, 70, 68),
  Height = c(170, 175, 160)
)

# Extract specific column
age_column <- my_data_frame$Age

# Print the result
cat("Data Frame:\n", my_data_frame, "\n")
cat("Extracted Age Column:", age_column, "\n")
# Given data frame
my_data_frame <- data.frame(
  Name = c("Alice", "Bob", "Charlie"),
  Age = c(25, 30, 22),
  Weight = c(65, 70, 68),
  Height = c(170, 175, 160)
)

# Extract specific rows and columns
selected_data <- my_data_frame[c(3, 5), c(1, 3)]

# Print the result
cat("Data Frame:\n", my_data_frame, "\n")
cat("Selected Data:\n", selected_data, "\n")
# Given data frame
my_data_frame <- data.frame(
  Name = c("Alice", "Bob", "Charlie"),
  Age = c(25, 30, 22),
  Weight = c(65, 70, 68),
  Height = c(170, 175, 160)
)



