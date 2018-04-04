# INTEX Sprint 3 Mailserver Implementation

This is assuming that everything in the lab works up to this point.

You should see the error that `Thunderbird failed to find the settings for email account`

First, change the firewall settings of your __Windows Advanced Firewall__

* Add SMTP and POP3

![alt text](https://raw.githubusercontent.com/clingeric/intex3/master/img/advanced.PNG)


![alt text](https://raw.githubusercontent.com/clingeric/intex3/master/img/newinboundrule.PNG)


![alt text](https://raw.githubusercontent.com/clingeric/intex3/master/img/port.PNG)


![alt text](https://raw.githubusercontent.com/clingeric/intex3/master/img/description.PNG)

Do the same for Tomato

Next, attempt to register your email account on Thunderbird, but use localhost or the loopback address on for the **Server Hostname** fields.

Click `re-test` and it should work, just like the lab

![alt text](https://raw.githubusercontent.com/clingeric/intex3/master/img/mailsetup.PNG)

When met with an error, continue onwards.

![alt text](https://raw.githubusercontent.com/clingeric/intex3/master/img/warning.PNG)

Change the SMTP Relayer info to use `gateway.byu.edu` and port `25`

![alt text](https://raw.githubusercontent.com/clingeric/intex3/master/img/hMailServer.PNG)

* This is found under Settings > Protocols > SMTP


Feel free to slack me `@clingeric` with any questions.
