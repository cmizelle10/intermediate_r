# intermediate_r
# while loop with break
# Initialize i as 1 
i <- 1

# Code the while loop
# Print i times 3; once i times 3 is divisible by 8, break the loop
while (i <= 10) {
  print(3 * i)
  if ((3 * i) %% 8 == 0) {
    break
  }
  i <- i + 1
}
