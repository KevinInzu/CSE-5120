library(MASS)
library(ISLR2)

attach(Auto)

#MPG (X)  as response, Horse power (Y) as predictor
lm.fit <- lm(mpg ~ horsepower)
summary(lm.fit)

confint(lm.fit)
predict(lm.fit,data.frame(horsepower = 98),interval = "confidence" )
predict(lm.fit,data.frame(horsepower = 98),interval = "prediction" )

plot(horsepower,mpg)
abline(lm.fit,col = "red")

par(mfrow = c(2,2))
plot(lm.fit)

