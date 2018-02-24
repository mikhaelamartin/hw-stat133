# 3: Technical Questions about Importing Data

# a. The headers are going to be auto-generated according to the first row of each column
# 
# b. It will return headers unnamed headers titled V1, V2, etc. 
# 
# c. It will remain as a character factor.
# 
# d. The first option will return everything that is not an integer into a factor, whereas the second option will return the intended data types. The data types will always be initally set up as factors.
# 
# e.It will return the character rownames, but will not display the proper information. Strings will return as NA

#data.matrix(data)


# 6: Techical Questions about data frames

# #A
# It will return an error: unexpected numeric constant in ...
# 
# #B
# 4
# 
# #C
# mpg is a vector, and cannot be indexed in the data frame without quotation marks. The brackets must either include a number to index or use quotation marks.
# 
# #D
# Yes, because a list is a vector and columns are composed of vertical vectors.
# 
# #E
# It will return the data with the correct information, but is separated by the column headers. Each column has its own separate list of elements in that vector(
#   
# #F
# Use as.data.frame(abc) to convert the object into a data frame
