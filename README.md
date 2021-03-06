# yadi.java 
YADI (Yet Another DLMS implementation) is a library for communication with metering devices using the DLMS standard. Check the wiki for code examples!

Master: [![Build Status](https://travis-ci.org/pfaco/yadi.java.svg?branch=master)](https://travis-ci.org/pfaco/yadi.java)
Dev: [![Build Status](https://travis-ci.org/pfaco/yadi.java.svg?branch=dev)](https://travis-ci.org/pfaco/yadi.java)

### Highlights
	* Application layer (COSEM) decoupled from link layer
	* HDLC and Wrapper as link layer protocols
	* MODE-E connection
	* PUBLIC/LLS/HLS authentication association
	* AUTHENTICATION/ENCRYPTION security
	* Long name referencing (no short name referencing yet)
	* Serial and TCP implementations provided

#### Dependencies:
	* JSSC (for serial communication)

## Changelog 


### Version 0.0.3a (2018.Feb.05)
Added tests
Solved bugs related to HDLC addressing

### Version 0.0.2a (2018.Feb.03)
Improved the documentation (javadoc) in the source code

### Version 0.0.1a (2018.Feb.03)
First released version.
