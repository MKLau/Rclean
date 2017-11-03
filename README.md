# cleanR

R is a great language for doing rapid, innovative analyses. 

Once you've gotten the results you want, leverage data provenance to
help clean your code up and focus on the specific results that you
really want.

Install
=======

Install the latest version easily with [devtools](https://github.com/hadley/devtools):

```R
library(devtools)
install_github("ProvTools/cleanR")
```

<<<<<<< HEAD
Clean up your code
==================

- Have you ever written a long script in R that conducts oodles of analyses and wished that someone would
  come along and make it all clearer to understand and use?
- Well you’re not alone. 
- A recent survey of over 1500 scientists reported a crisis of reproducibility with "slective reporting" being 
  the most cited contributing factor and 80% saying code availability is playing a role
- We created **cleanR** to help scientists more *easily* write "cleaner" code
- [cleanR](https://github.com/ProvTools/cleanR) provides a simple way get the code you need to produce a specific result
- **cleanR** uses data provenance tp capture what your code actually
  does when it’s running and then allows you to pull out the essential
  code that produces specific outputs.
- Here’s a simple example:
=======
You'll also need the [provR](https://github.com/ProvTools/provR)
package to capture the data provenance that informs [cleanR](https://github.com/ProvTools/cleanR).

>>>>>>> ddf307d5b278e027df6b744a2f3649c89cd96fbf
```R
install_github("ProvTools/provR")
```
- [Checkout a demo of how to use the package!](http://tinyurl.com/ProvTools-cleanR)
- By focusing in on the specific results you want, **cleanR** let’s
  you spend more energy on your science and less time figuring out
  your code.




<<<<<<< HEAD
=======
Clean some code
===============

[cleanR](https://github.com/ProvTools/cleanR) provides a simple API to
hone in on a specific result that you want from your script and return
the code you need to produce it.

![cleanR-demo](cleanR-demo.gif)

>>>>>>> ddf307d5b278e027df6b744a2f3649c89cd96fbf
