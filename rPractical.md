# Practical1: Using R execute the basic commands, array , list and frames

``` 
num_vec <- c(1, 2, 3, 4, 5)
char_vec <- c("apple", "banana", "cherry")
print(num_vec)
print(char_vec)
print(class(num_vec))
print(class(char_vec))

#matrix command
mat <- matrix(1:9, nrow = 3, ncol = 3)
print(mat)
print(class(mat))

#list command
my_list <- list(1, "apple", TRUE, 3 + 4i)
print(my_list)
print(class(my_list))

#dataframes
df <- data.frame(
  numbers = c(1, 2, 3),
  fruits = c("apple", "banana", "cherry"),
  logicals = c(TRUE, FALSE, TRUE)
)


print(df)
print(class(df))
```

# Practical2: Create matrix using R and perform the operation addition, multiplication, division

```
#Creating First matrix  
#Creating First matrix  
myMatrixA <- matrix(c(1, 2, 3, 4, 5, 6,7,8,9), nrow = 3, ncol = 3)   
myMatrixA 

#Creating Second matrix  
myMatrixB <- matrix(c(9,8,7,6,5,4,3,2,1), nrow = 3, ncol = 3)   
myMatrixB  

#Adding Both Matrices  
myMatrixCAfterAdding <- myMatrixA - myMatrixB  
myMatrixCAfterAdding  

#Creating matrices
matrixm<- matrix(1:8, nrow=2)
matrixm
matrin<- matrix(8:15, nrow=2)
matrin

#Multiplying matrices
print(m*n)



#Creating matrices
matrixm<- matrix(1:8, nrow=2)
matrixm
matrixn<- matrix(8:15, nrow=2)
matrixn

#division matrices
print(matrixm/matrixn)
```

