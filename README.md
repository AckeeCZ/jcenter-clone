# jCenter clone

This repository contains depenencies used on Ackee projects which are still hosted on a jCenter. These are usually no longer maintained dependencies, eg. Anko, which we can't easily get rid of. 

To use it in your project add this to your repositories setup instead of a jCenter. Don't forget to include also mavenCentral

```groovy
+  maven { url "https://raw.github.com/AckeeCZ/jcenter-clone/main" }
```

