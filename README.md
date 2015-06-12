# aeBIAB Firmware

This code will borrow learn from the BrewPi spark-firmware, in order to produce a fully automatic brewery. As the brewery design is an original design (more at: [aebiab.com](www.aebiab.com)), the firmware requires extensive change. In all honestly, temperature control and prediction is the key component I'm keen on reviewing. Even communication between the Pi and 2560 will need an extention to the schema to suit my needs.

This firmware originally depends on two other libraries: the [Spark Common Library](http://www.github.com/spark/core-common-lib) and the [Spark Communication Library](http://www.github.com/spark/core-communication-lib), however these functions will be rewritten using either native library functions, or will be written.


## Where to Start?
Let's begin by working on our requirements, expectations and hopefulyl produce a nice schema. 
