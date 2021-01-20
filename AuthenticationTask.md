# User authentication journey

Many of you have probably already came across the terms **Authentication** and **Authorisation**. Although, they sound quite similar, they mean and perform actions much different from each other. In this article, I would like to tell you the difference between these two terms and give you some examples of benefits and difficulties which you can encounter while using these.

## Authentication as authorisation

Imagine  it is your first day at a new workplace. You get an office badge and a new laptop. Everything feels so new and exciting but one thing remains the same as in your previous job. You need to get somehow into the offica and log into your new computer with password and then configure all the necessary stuff. In other words, your office, your new computer and the software on it needs to know that when YOU log in it is really you!

Here comes the **authentication**. First, you enter your credentials given to you by your new manager (or IT departament). Your login is your company email address. The password is already set but you will probably be forced to change it during your first access. After some time the whole process should be finished but how they know it is you? The system communicates with the database where the information is stored, compares your input and checks if it is correct, your web browser verifies the digital signature of the server certificate and... Success, you are in! But why you cannot install some additional software such as Spotify or IDE you will be working on? Simple. You do not have the permission to do so.

You have succesfully authenticated yourself to the system but you are not **authorised** to perform certain actions. The authorisation process is done after you authenticate yourself to the system. In other words, the access to a desired resource is a two-step process. First, you have to be authenticated and then authorised. You are assigned to a particular role in your company, meaning you will not have access to some of the company stuf your manager or the CEO  will. Your permissions are limited to your particular role.

## Multi-Factor Authentication (MFA)

 In modern identity management and security systems it is not enough to just simplu enter your login and password. For example, your company uses Microsoft solutions. You may be asked to download the Authenticator app, log into it with your company credentials and set another "step" of defining that you are you. You have a variety of additional security levels. You may set a PIN code, add your fingerprint (biometric authentication) or type a one-time short code, which will expire after 90 seconds.

 ![MFA Authentication](https://www.avatier.com/blog/wp-content/uploads/2018/03/blog-mfa-how-it-works.jpg "MFA Authentication")

## Continuous Risk-based Authentication (RBA)

Alright, so you entered your credentials, authenticated yoursef with biometrics, everything seems just fine, but there can be some additional safety measures implemented into the system. More and more companies use the Risk-based authentication (RBA). The RBA checks the logging method in real time. These are taken into consideration:

* Device
* Location
* IP address
* Confidentiality of the resource

After all the data is checked, the system makes the real-time decision if you will be allowed to the information you are trying to access. It can either let you through as usual or you will be asked to provide some additional information, so that the system is certain that it is you.

The most important benefit of using RBA is clearly the safety of your data. You can detect any suspicious and unauthorised access to your mailbox or a bank account because, most likely, you will receive a notification. However, some drawbacks of such approach may also emerge. The evil does not sleep, meaning, the system which estimates the risk has to be continuously updated and maintained because new threats appear. They say "time is money" and such approach is time consuming. The people may find it frustrating to authenticate themselves additionally each time they change location or a device from which they try to gain access. Last but not least, a bad implementation of the RBA may result in giving access to the sensitive data to the unauthorised people or block access to the data for the rightful users.