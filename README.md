# R-LANGUAGE
LEARNING ABOUT R LANGUAGE
<- is the assignment operator.
# character is used to indicate a comment(right side of # is ignored)
for eg->x<-1
>print(x)- Is explicit printing
>x-  Is auto printing
In output we get [1] before answer ,this represent that x is a vector.

There are 5 basic classes of objects-character,numeric,integer,logical,complex.
Most basics object is-vector.
Vector is a object that contains objects of same class.
list is an exception that contains objects of different classes.
Inf-represent infinite no.
NaN -Not a number
NA -not applicable


vectors and list
c()-create vector of object
>x<-c(0.2,0.4)    #numeric
vector() function can also be used to do the same .
When vector is created and they are of different classes then COECION happens.
>s<-c(1,"true") ----then the result is character.
Explisit coesion can also be done by using the function ----  as.classname
for eg.->x<-c(1,2,3)
    >as.logical(x)
    [1] T T T
    
