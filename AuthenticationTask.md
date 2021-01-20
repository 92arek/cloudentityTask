# User authentication journey

Many of you have probably already came across the terms **Authentication** and **Authorisation**. Although, they sound quite similar, they mean and perform actions much different from each other. In this article, I would like to tell you the difference between these two terms and give you some examples of benefits and difficulties which you can encounter while using these.

## Authentication as authorisation

Imagine  it is your first day at a new workplace. You get an office badge and a new laptop. Everything feels so new and exciting but one thing remains the same as in your previous job. You need to get somehow into the offica and log into your new computer with password and then configure all the necessary stuff. In other words, your office, your new computer and the software on it needs to know that when YOU log in it is really you!

Here comes the **authentication**. First, you enter your credentials given to you by your new manager (or IT departament). Your login is your company email address. The password is already set but you will probably be forced to change it during your first access. After some time the whole process should be finished but how they know it is you? The system communicates with the database where the information is stored, compares your input and checks if it is correct, your web browser verifies the digital signature of the server certificate and... Success, you are in! But why you cannot install some additional software such as Spotify or IDE you will be working on? Simple. You do not have the permission to do so.

You have succesfully authenticated yourself to the system but you are not **authorised** to perform certain actions. The authorisation process is done after you authenticate yourself to the system. In other words, the access to a desired resource is a two-step process. First, you have to be authenticated and then authorised. You are assigned to a particular role in your company, meaning you will not have access to some of the company stuf your manager or the CEO  will. Your permissions are limited to your particular role.

## Multi-Factor Authentication (MFA)

 In modern identity management and security systems it is not enough to just simplu enter your login and password. For example, your company uses Microsoft solutions. You may be asked to download the Authenticator app, log into it with your company credentials and set another "step" of defining that you are you. You have a variety of additional security levels. You may set a PIN code, add your fingerprint (biometric authentication) or type a one-time short code, which will expire after 90 seconds.

 ![MFA Authentication](https://www.avatier.com/blog/wp-content/uploads/2018/03/blog-mfa-how-it-works.jpg "MFA Authentication")

#
