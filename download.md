---
layout: default
title: Download
---
 
## Installing BPELUnit in Eclipse

For users, the simplest way of installing BPELUnit is to use the update 
site. In the Help menu, choose Software Updates..., where you choose the 
Available Software tab. Click Add Site... and enter 
[`http://update.bpelunit.net`](http://update.bpelunit.net) as the 
new site's location. Click OK. 

Alternatively, you can use the zipped update site available
[here](http://search.maven.org/remotecontent?filepath=net/bpelunit/eclipse-update-site/1.6.0/eclipse-update-site-1.6.0-assembly.zip).

Once the BPELUnit Update Site is added, simply check BPELUnit Update 
Site, click Install... and follow the instructions. After Eclipse has 
restarted, BPELUnit should be installed. 

You can verify the installation by opening the plugin information dialog 
(Help / About Eclipse Platform / Plug-in Details) and look for BPELUnit. 
You should have three plugins. 

For getting started with how to use BPELUnit, please refer to the two 
tutorials: 

 + Testing a Hello World Process
 + Testing a Simple BPEL Process with Mocking

## Installing BPELUnit standalone

If you do not use Eclipse or you want to also use its Apache Ant task,
you will need to have the standalone version of BPELUnit.

Download it from
[here](http://search.maven.org/remotecontent?filepath=net/bpelunit/dist/1.6.1/dist-1.6.1-standalone.tar.gz)
and extract it to any directory, e.g. `C:\Program Files\` under
Windows. For starting BPELUnit in Windows, a batch file bpelunit.bat
is supplied. For the batch file to work, you have to set
`BPELUNIT_HOME` to the BPELUnit directory and `JAVA_HOME` to your Java
installation directory.
