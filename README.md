JMeter OAuth
============
Apache JMeter OAuth. Implements a JMeter sampler called "OAuth Request". It's based on HTTP Request with HTTPClient and supports OAuth signing.

Code based on https://github.com/captrespect/jmeter-oauth. This version is enhanced to not send an empty OAuth Token to the endpoint if 2-legged OAuth is used.

Requirements
------------
* JMeter 2.11

Build
-----
Replace `$JMETER_PATH` with your JMeter path.

```
$ ./gradlew fatJar
$ mv jmeter-oauth/build/libs/ApacheJMeter_oauth-2.1.jar $JMETER_PATH/lib/ext
```

Usage
-----
Once installed, you should see "OAuth Request" in the Sampler menu.
