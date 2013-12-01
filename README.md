
## FITNESSE RUNNER ##


After downloading the fitnesse jar file copy it to FitnesseRunner/lib based on your environment start the appropriate script, you are done.

Fitnesse Runner is based on [Java Service Wrapper][jswId]
![Java Service Wrapper][jswImageId]

### FEATURES ###

---

* Pre bundled script which would allow you to manage fitnesse instance in different environments seamlessly
* Configurations can be changed/added very easily
* Scripts supports init.d configuration and Windows Service modes
* Upgrading Fitnesse is just a matter of replacing __fitnesse.jar__ in lib folder
* you can added other jar (scm jar for example) files easily in the class path
* _application parameters_ and _jmv parameters_ can configured very easily


### DIRECTORY DETAILS ###

---


* __data__ ==> This is where Fitnesse will store all the its data.

* __logs__ ==> this where Fitnesse will spit out logs

* __conf__ ==> configuration that should be done to Fitnesse/JSW is driven through files in this folder

* __lib__ ==> this folder contains __wrapper.jar__ and __fitnesse.jar__

* __bin__ ==> binary executables are present here, based on you environment you have to execute one of the files in this directory

---

### FAQ ###

---


#### How do I change the port? ####


__If you want to change the port, change the following paramer (line number 51 of FitnesseRunner/conf/wrapper.conf__

	wrapper.app.parameter.3=9080



  [jswId]: http://wrapper.tanukisoftware.com/  "Java Service Wrapper"
  [jswImageId]: http://wrapper.static.tanukisoftware.co.jp/images/jsw-logo.jpg "Java Service Wrapper"
