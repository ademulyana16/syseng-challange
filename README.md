# syseng-challenges

Question-One :

-Basic Linux

```
a. Please provide a cronjob to Housekeeping log in /var/log/nginx/ if log more than 14 days 
b. Please provide a logrotate script in /etc/logrotate.d/ to compress log in /var/log/nginx/ if more than 100MB
```
Question-two :

-Linux Administration

Our company has made in-house application to track all of employee performance. But the specs of the server itself put on the mininum specification, so we must pointing every users to access the server which has least connection. so we setup another VM to run HAProxy as our load balancer/reverse as a service and here IP address of server application and the link to access to the application.

- appservern1 : 10.10.1.1
- appservern2 : 10.10.1.2
- url : https://lb-application.com

```
Please provide file of /etc/haproxy/haproxy.cfg to do the the job
```
*Note : the application must always access through https  

Question-Three :

-Zimbra

Assuming you are Zimbra Administrator in our company, suddenly we have spam attack to our organization with this details below:
```
- From : itadmin@xyz.com ; (207.18.13.24)
- Subject : YOUR PASSWORD HAS BEN EXPIRED
- to : all member
```

To prevent it we should recall all the spam email from every mailbox. But, before we do that other Zimbra admin already search all the spam email using content search with "20211110_corpinfo" as a name

```
a. Tell us step-by-step to prevent that spam attack appear again in our mailbox
b. Please provide shell script to recall the spam mail from every mailbox
```
