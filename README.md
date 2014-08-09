SplunkBlack
==============

Basic app for querying Microsoft sysmon data from the eventlog and sending into Splunk. May be helpful for building a ghetto HIDS.

This code is entirely based on Jason Conger's code here: https://github.com/JasonConger/SplunkWinLogon 

App Installation
================


Addon (TA) Installation
=======================

0. Ensure the powershell script policy 
1. Install the Splunk Universal Forwarder on the systems you want to monitor.
2. Copy $SPLUNK_HOME/etc/apps/SplunkBlack/appserver/addons/TA-SplunkBlack to $SPLUNK_HOME/etc/apps/TA-SplunkBlack

The final folder structre should look like this:

    C:\

        Program Files\

            SplunkUniversalForwarder\
            
                etc\
                
                    apps\
                    
                        TA-SplunkBlack
