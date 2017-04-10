[![Build Status](https://travis-ci.org/rapid7/r7insight_java.png?branch=master)](https://travis-ci.org/rapid7/r7insight_java)

[Please see our wiki for full documentation and installation](https://github.com/rapid7/r7insight_java/wiki)
-------

Logging To Logentries from Java
==============================

Logentries currently supports logging from Java using the following logging libraries:

* [Log4J](https://github.com/rapid7/r7insight_java/wiki/Log4j)
* [Log4J2](https://github.com/rapid7/r7insight_java/wiki/Log4j2)
* [Logback](https://github.com/rapid7/r7insight_java/wiki/Logback)
* [Java Util Logging](https://github.com/rapid7/r7insight_java/wiki/Java-Util-Logging)

-------

Account Setup
=============

You can sign up for a Logentries account [here](https://logentries.com/quick-start/). Once you have your credentials and have logged in,
create a new host in the UI with a name that represents your app. Then, select this host and create a new logfile with a name that represents what you're
logging. Select 'TOKEN TCP' as the source_type and click Register to create the log.

-------

Maximum Log Length
==================

Currently logs which exceed 65536 characters in length, including any patterns and timestamps you may include, will be split and sent as multiple logs.

-------
