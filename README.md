About¶

matlabcontrol is a Java API that allows for calling MATLAB from Java. You can eval, feval, as well as get and set variables. Interaction can be performed from either inside MATLAB or outside MATLAB. 

Version 4 adds many feature requests including reconnecting to a previously controlled MATLAB session, running MATLAB hidden, and better handling of returned data. To see exactly what has changed, consult the version history page. 

Getting Started¶

The basic usage pattern with matlabcontrol is to create a factory, and then to create a proxy. The proxy is used to communicate with MATLAB. 
MatlabProxyFactory factory = new MatlabProxyFactory();MatlabProxy proxy = factory.getProxy();...//Use the proxy as desired...proxy.disconnect();
To find out how to use the proxy, start reading the walkthrough. 

Walkthrough - Explains how to use matlabcontrol. 

javadocs - Full javadoc documentation of matlabcontrol. 

FAQ - Frequently (and some infrequently) asked questions about matlabcontrol. 

Bugs

If you encounter a bug, please file it with as much information as you have. 

Compatibility¶

This API relies upon the Java MATLAB Interface distributed with all recent copies of MATLAB. This interface is entirely undocumented and there is no guarantee matlabcontrol will work with all versions of MATLAB and operating systems. Efforts are made to ensure compatibility with MATLAB R2007b and greater, see here for specifics. 

Announcements¶

March 1, 2013 

Version 4.1.0 has been released! It includes minor additions and bug fixes. See the version history page for more information. 

Older announcements can be found here. 

--------------------------------------------------------------------------------

There are a variety of approaches to controlling MATLAB from Java, each with multiple solutions. To see which approach makes the most sense for your needs, please read this page which provides overviews and links. 

--------------------------------------------------------------------------------


The icon for matlabcontrol is part of the Um collection created by mattahan (Paul Davey). It is licensed under the CC Attribution-Noncommercial-Share Alike 3.0 License. 


