fuse-xmlsec-demo
================

This is a reproducer for a Santuario XMLSec problem in Fuse 6.1.redhat-379.

To use this reproducer, simply do a "mvn clean install", then do the following
Fuse/Karaf command from a fresh Fuse install:

    osgi:install -s mvn:org.overlord/fuse-xmlsec-demo/0.0.1-SNAPSHOT
