Android Service

The Paho Android Service is an interface to the Paho Java MQTT client library that provides a long running service for handling sending and receiving messages on behalf of Android client applications when the applications main Activity may not be running.

The Paho Android Service provides an asynchronous API

Source
http://git.eclipse.org/c/paho/org.eclipse.paho.mqtt.java.git/

Building from source
The Paho Android Service is contained within the Paho Java client repository which can be cloned from git with the following command

git clone http://git.eclipse.org/gitroot/paho/org.eclipse.paho.mqtt.java.git

The source code for the Paho Android Service can be found in the directory org.eclipse.paho.android.service/org.eclipse.paho.android.service relative to the directory the git repository was cloned into in the previous step.

There are two other directories in org.eclipse.paho.android.service, org.eclipse.paho.android.service.sample which contains the source code to a sample application, and org.eclipse.paho.android.service.test which contains tests for the Android Service

All three directories are also setup as eclipse projects that can be imported into an eclipse instance that has the Android Development Tools installed.

When building the Paho Android Service from source you should ensure that an appropriate version of the Paho Java client library jar file has been copied into org.eclipse.paho.android.service/org.eclipse.paho.android.service/libs

Download
The Paho Android Service jar can be downloaded from:here

When developing Android applications you will require both the Paho Android Service jar and the Paho Java Client library jar.

Documentation
Reference documentation is online at: http://www.eclipse.org/paho/files/android-javadoc/index.html

Getting Started

A sample application in source code form is included in the org.eclipse.paho.android.service.sample directory. Click here to read the details of the getting started section.