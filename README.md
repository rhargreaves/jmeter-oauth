jmeter-oauth
============
Apache JMeter OAuth. 

Original code at https://github.com/captrespect/jmeter-oauth

Updated to work with JMeter 2.11

This JAR implements a JMeter sampler called "OAuth Request". 
It's based on HTTP Request with HTTPClient and supports 
OAuth signing. 

To buid, run gradle in the project root directory

gradle fatJar

This will build the jar file in build/libs directory. OAuth 
library is also included in the jar.

To install the plugin, download the binary distribution of 
JMeter and copy the JAR file to lib/ext directory
under JMeter.

Once correctly installed, you should see "OAuth Request"
in sampler menu, right beneath "Mail Reader Sampler".
