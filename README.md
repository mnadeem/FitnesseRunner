
## FITNESSE RUNNER ##


After downloading the fitnesse jar file copy it to FitnesseRunner/lib based on your environment start the appropriate script, you are done.

---

### DIRECTORY DETAILS ###


* __data__ ==> This is where Fitnesse will store all the its data.

* __logs__ ==> this where Fitnesse will spit out logs

* __conf__ ==> configuration that should be done to Fitnesse/JSW is driven through files in this folder

* __lib__ ==> this folder contains __wrapper.jar__ and __fitnesse.jar__

* __bin__ ==> binary executables are present here, based on you environment you have to execute one of the files in this directory

---

### FAQ ###


##### How do I change the port? #####


__If you want to change the port, change the following paramer (line number 51 of FitnesseRunner/conf/wrapper.conf__

_wrapper.app.parameter.3=9080_

---

