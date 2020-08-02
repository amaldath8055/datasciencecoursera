HelloWorld
==========

## This is a markdown file
xo<-1
tol<-1e-8
repeat{
x1<_computerEstimate()
if(abs(x1-xo))< tol {
  break
} else {
      xo<-x1
}
}
