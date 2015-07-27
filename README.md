# burp-api

The [Burp Suite](https://portswigger.net/burp/) API is distributed as a set of .java files containing interface specifications. Commonly, these files are compiled and included in a JAR with Burp extensions. These files are not needed in the final JAR, however, as the interfaces are already implemented by Burp itself. We wanted an easier way to build Burp extensions without having these unnecessary files taking up space in our IDEs and JARs.

The aim of this project was to create a repeatable process for packaging the Burp API files into a JAR for use in developement and compilation of Burp extensions. Simply place this JAR in your IDE's or compiler's classpath.
