[![Travis status](https://travis-ci.org/econtoolkit/Expectations.jl.svg?branch=master)](https://travis-ci.org/econtoolkit/Expectations.jl)

# Expectations

Installation:
```julia
Pkg.clone("http://github.com/econtoolkit/Expectations.jl.git")
```

This is a WIP package designed to help with taking expectations of functions of random variables (i.e., defining an expectation operator `E` that could be applied `Ef(X)`). 

The underlying random variables are designed around the `Distributions.jl` interface. 

This implementation is designed around v0.6. 
