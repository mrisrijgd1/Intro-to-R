# Intro-to-R
## Vector
#This is a vector.

```{r}
vector <- c(1,2,3,4,5)
```

## Strings
#We learnt that vectors can hold strings.

```{r}
vs <- c("Krishna", "Mridul", "Srishti", "Niyati")
```

## Mean
#Mean is basically adding numbers and divided by the count.

```{r}
vector <- c(1,2,3,4,5)
mean(vector)
```
## Matrix
#Matrix is a table with rows and collumns.

```{r}
mat.mridul <- matrix(1:8, 2, 4)
dim(mat.mridul)
mean(mat.mridul)
mean(c(1,2,3,4,5,6,7,8))
```

## Plot
#We learnt about plotting below is an example of scatter plot. 

```{r}
age <- c(13, 13, 16, 16, 11.5, 11, 8)
weight <- c(48, 60, 50, 32, 34, 28,  48)
plot(x=age,y=weight, main="Age Group", xlab = "Age",         ylab = "Weight", pch=19, col="red")
# Add fit lines
abline(lm(weight~age), col="red") # regression line (y~x)
lines(lowess(age, weight), col="blue") # lowess line (x,y)


```
