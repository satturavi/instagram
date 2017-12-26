13 July 2017
                                                     Apache Lounge Distribution VC10

                                                Apache 2.2.34 Win64 with openssl-1.0.2l

Original Home: httpd.apache.org
Binary by: Steffen
Mail: info@apachelounge.com
Home: www.apachelounge.com


Build with Visual Studio® 2010 SP1 (VC10) x64
---------------------------------------------

Be sure you have installed the Visual C++ 2010 SP1 Redistributable Package x64,
download and install, if you not have it already, see:

  https://www.apachelounge.com/download/win64/


Minimum system required
-----------------------

Windows 8 / 8.1
Windows 7
Windows 10
Windows Server 2016
Windows Server 2012 / R2
Windows Vista 
Windows Server 2008 / R2  
Windows XP SP3 
Windows Server 2003 R2 / SP1

Install
-------

- Unzip the apache2 folder to c:/Apache2 (that is the ServerRoot in the config).
  Default folder for your your webpages is DocumentRoot "c:/Apache2/htdocs"

  When you unzip to an other location, change ServerRoot in the httpd.conf,
  and change in httpd.conf the Documenroot, Directories, ScriptAlias,
  also when you use the extra folder config file(s) change to your location there. 

Start apache in a DOS box:

>httpd.exe

Install as a service:

>httpd.exe -k install

ApacheMonitor:

Double click ApacheMonitor.exe, or put it in your Startup folder.



Upgrading
---------

- Updating from 2.2.x
  copy all the files over, except your changed .conf files.

- Updating httpd.apache.org 2.2.x distribution
  copy all the files over, except your changed .conf files.

- Upgrading from 2.0.x see: httpd.apache.org/docs/2.2/upgrading.html
  and see httpd.apache.org/docs/2.2/new_features_2_2.html .


When you have questions or want more info, post in the forum at www.apachelounge.com or mail me.

Enjoy,

Steffen



Legal note:

   This distribution includes cryptographic software.  The country in 
   which you are currently may have restrictions on the import, 
   possession, and use, and/or re-export to another country, of 
   encryption software.  BEFORE using any encryption software, please 
   check the country's laws, regulations and policies concerning the
   import, possession, or use, and re-export of encryption software, to 
   see if this is permitted.

   The U.S. Government Department of Commerce, Bureau of Industry and
   Security (BIS), has classified this software as Export Commodity 
   Control Number (ECCN) 5D002.C.1, which includes information security
   software using or performing cryptographic functions with asymmetric
   algorithms.  The form and manner of this Apache Software Foundation
   distribution makes it eligible for export under the License Exception
   ENC Technology Software Unrestricted (TSU) exception (see the BIS 
   Export Administration Regulations, Section 740.13) for both object 
   code and source code.

   The authors of the represented software packages and me, are not
   liable for any violations you make. Be careful, it is your responsibility. 

