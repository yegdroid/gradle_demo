A simple demo of the gradle build system. 

There are a couple of things to note that took me a while to figure out:

* `classpath 'com.android.tools.build:gradle:0.3'` I had to use plugin version 3
* `compileSdkVersion 17` this needed to be present in the android->default config section to build properly
* sigining keys: use gradle.properties to set the password for store, key and location to keep your keys out of the repo 
