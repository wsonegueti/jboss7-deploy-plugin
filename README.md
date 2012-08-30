tfs-build-update-plugin
=======================

Jenkins plugin that updates a Team Foundation Server build

Download and install the Tfs Sdk for Java (version 11.0.0) into your local maven repo using the following command:

mvn install:install-file -Dfile=com.microsoft.tfs.sdk-11.0.0.jar -DgroupId=microsoft -DartifactId=tfs-sdk -Dversion=11.0.0 -Dpackaging=jar -DgeneratePom=true