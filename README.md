# FIRST

```
function test() {
  console.log("notice the blank line before this function?");
}
```

# The largest heading
## The second largest heading
###### The smallest heading

**This is bold text**
*This text is italicized*
~~This was mistaken text~~
**This text is _extremely_ important**

```
x   <- seq(0,1, length=100)
hx  <- dbeta(x,shape1=0.5,shape2=0.5)
hx1  <- dbeta(x,shape1=1,shape2=1)
hx2 <- dbeta(x,shape1=2,shape2=5)
hx3 <- dbeta(x,shape1=50,shape2=40)

hxtest <- dbeta(x,shape1=3,shape2=17)
plot(x, hx, type="l", lty=2, ylim=c(0,8),xlab="x value",
     ylab="Density", main="Comparison of Beta Distributions")
lines(x,hx1,col="red")
lines(x,hx3,col="green")
lines(x,hxtest,col="blue")
```
