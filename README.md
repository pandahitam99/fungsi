# fungsi


#fungsi R by ivanda 
#Constan function
f <- function(x){
  fx <- 2
  return(fx)
}

input <- 0:5
plot(input, sapply(input, f), type = "l", xlab = "x", ylab = "f(x)")
f(3)
f(input)


#Linear Function
linear <- function(x){
  fx <- 2 * x + 4
  return(fx)
}
input <- 1:4
plot(input, sapply(input, linear), type = "l", xlab = "x", ylab = "f(x)")
linear(input)

#Quadratic Function
quadratic <- function(x){
  fx <- 1*x^2 + 2*x + 3
  return(fx)
}

input <- 1:3
plot(input, sapply(input, quadratic), type = "l", xlab = "x", ylab = "f(x)")
quadratic(input)

#Polynomial function
polynormial <- function(x){
  fx <- 1*x^3 + 2*x^2 + 3*x + 4
  return(fx)
}

input <- 1:3
plot(input, sapply(input, polynormial), type = "l", xlab = "x", ylab = "f(x)")
polynormial(input)

#Rational function
rational <- function(x){
  fx <- 1*x / 2*x
  return(fx)
}

input <- -1 : 3
plot(input, sapply(input, rational), type = "l", xlab = "x", ylab = "f(x)")
rational(input)

