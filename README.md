#my first r programming language
myString<-"Hello,World!"
print(myString)

#create a vector
apple<-c('red','green',"yellow")
print(apple)
#get the class of vector
print(class(apple))

#Create a List.
list1 <-list(c(2,5,3),21.3,sin)
#print the list
print(list1)

#Create a matrix
M=matrix(c('a','a','b','c','b','a'),nrow=2,ncol=3,byrow=TRUE)
print(M)

#Create an array
a <- array(c('green','yellow'),dim = c(3,3,2))
print(a)

#Create a vector
apple<-c('green','green','yellow','red','red','red','green')
#Create a factor object.
factor<-factor(apple)
#Print the factor
print(factor)
print(nlevels(factor))

#Create the data frames
BMI<- data.frame(
  gender=c("Male","Male","feMale"),
  height=c(152,171.5,155),
  weight=c(81,93,78),
  Age=c(42,38,25)
)
print(BMI)

#Assignment using equal operator
var.1=c(0,1,2,3)

#Assignment using leftward operator
Var.2=c("learn","R")

#Assignment using righward operator
c(TRUE,1)->var.3

print(var.1)

cat("var.1 is",var.1,"\n")

cat("Var.2 is",Var.2,"\n")

cat("var.3 is",var.3,"\n")

var_x<-"Hello" 
cat("The class of var_x is",class(var_x),"\n" )  
 
var_x<-34.5
cat("Now The class of var_x is",class(var_x),"\n" )

var_x<-27L
cat("Next The class of var_x is",class(var_x),"\n" )

print(ls())

#List the variables starting with the pattern "var".
print(ls(pattern="var"))

print(ls(all.name=TRUE))

rm(var.3)
Print(var.3)

rm(list=ls())
print(ls())

#operators

#Arathmetic operator
v<-c(2,5,7)
t<-c(8,3,4)
#To Add two vectors
print(v+t)
#To subtract two vectors
print(v-t)
#To Multiply both vectors
print(v*t)
#To Divide the first vector with the second
print(v/t)
#TO give the remainder of the first vector with the second
print(v%%t)
#To produce The result of division of first vector with second(quotient)
print(v%/%t)
#To raise the first vector to the exponent of second vector
