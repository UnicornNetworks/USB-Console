`has-console-access: false`

# Discussion
https://community.cisco.com/t5/small-business-routers/accessing-the-cli-on-a-rv340w-via-putty/td-p/3323015

"  Martin Aleksandrov Cisco Employee Cisco Employee
In response to RustyPearce2027
‎04-03-2021 02:15 AM
@RustyPearce2027 

 

There is no plan to enable the console port and productise the CLI access to the RV series routers.


Martin Aleksandrov Cisco Employee Cisco Employee
In response to UNHAPPY666!
‎04-05-2021 12:27 AM
Console port/CLI access and the cable have never been identified in any marketing materials as major product features. The cable is not even listed in the included accessories in the product datasheet. The console port is mentioned for future use only and disabled.

Jo Kern
  Jo Kern Cisco Employee Cisco Employee
In response to paulCuda35500
‎05-03-2019 07:52 AM
 

Upgrading to a new firmware should not impact user authentication.

If you get a user login via the browser it seems that your connectivity is ok.

If this is brand new router and you uploaded only the firmware please do a factory reset using the physical reset button on the device.

We have tested multiple upgrade scenarious and have not seen this issue.

In the newer firmware we restrict access to management from user VLANs. So you need to be on the default management VLAN.

The console port is for troubleshooting and can only be enabled by Cisco support
"
