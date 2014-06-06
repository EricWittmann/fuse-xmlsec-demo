fuse-xmlsec-demo
================

This is a reproducer for a Santuario XMLSec problem in Fuse 6.1.redhat-379.

To use this reproducer, simply do a "mvn clean install", then do the following
Fuse/Karaf command from a fresh Fuse install:

    osgi:install -s mvn:org.overlord/fuse-xmlsec-demo/0.0.1-SNAPSHOT

If the test passes, you will see a simple message in the fuse shell.  If the 
test fails (expected with redhat-379 of Fuse) you will see a message followed
by a ClassCastException stack trace.

