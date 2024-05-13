
https://tryhackme.com/r/room/phishingemails1tryoe
https://tryhackme.com/room/phishingemails2rytmuv](https://tryhackme.com/room/phishingemails2rytmuv

The invention of the email dates back to the 1970s for [ARPANET](https://www.britannica.com/topic/ARPANET). 
So, what makes up an email address?  

1. **User Mailbox (or Username)**
2. **@**
3. **Domain**

Let's look at the following email address, billy@johndoe.com.

1. The **user mailbox** is billy
2. **@** 
3. The **domain** is johndoe.com

There are 3 specific protocols involved to facilitate the outgoing and incoming email messages, and they are briefly listed below.

- **SMTP** (**Simple Mail Transfer Protocol)** - It is utilized to handle the sending of emails. 

- **POP3 (Post Office Protocol)** - Is responsible transferring email between a client and a mail server. 

- **IMAP (Internet Message Access Protocol)** - Is responsible transferring email between a client and a mail server. 

You should have noticed that both **POP3** and **IMAP** have the same definition. But there are differences between the two.

The difference between the two is listed below: 

**IMAP (Internet Messaging Access Protocol)**

• Emails are stored on the server.  
• Sent messages are stored on the server.  
• Messages can be synced and accessed across multiple devices.

**POP3 (Post Office Protocol)**

• Emails are stored on a single device.  
• Sent messages are stored on a single device.  
• Emails can only be accessed from a single device.  
• If you want to keep messages on the server, make sure the setting "Keep email on server" is enabled or all messages are deleted from the server once downloaded to the app or software.

## There are two parts to an email:

- the email **header** (information about the email, such as the email servers that relayed the email)
- the email **body** (text and/or HTML formatted text)

The syntax for email messages is known as the **[Internet Message Format](https://datatracker.ietf.org/doc/html/rfc5322)** (**IMF**).


Different type of phishing : 

Different types of malicious emails can be classified as one of the following:

- **[Spam](https://www.proofpoint.com/us/threat-reference/spam)** - unsolicited junk emails sent out in bulk to a large number of recipients. The more malicious variant of Spam is known as **MalSpam**.
- **[Phishing](https://www.proofpoint.com/us/threat-reference/phishing)** -  emails sent to a target(s) purporting to be from a trusted entity to lure individuals into providing sensitive information. 
- **[Spear phishing](https://www.proofpoint.com/us/threat-reference/spear-phishing) -** takes phishing a step further by targeting a specific individual(s) or organization seeking sensitive information.  
- **[Whaling](https://www.rapid7.com/fundamentals/whaling-phishing-attacks/)** - is similar to spear phishing, but it's targeted specifically to C-Level high-position individuals (CEO, CFO, etc.), and the objective is the same. 
- [**Smishing**](https://www.proofpoint.com/us/threat-reference/smishing) - takes phishing to mobile devices by targeting mobile users with specially crafted text messages. 
- [**Vishing**](https://www.proofpoint.com/us/threat-reference/vishing) - is similar to smishing, but instead of using text messages for the social engineering attack, the attacks are based on voice calls.

Below are typical characteristics phishing emails have in common:

- The **sender email name/address** will masquerade as a trusted entity (**[email spoofing](https://www.proofpoint.com/us/threat-reference/email-spoofing)**)
- The email subject line and/or body (text) is written with a **sense of urgency** or uses certain keywords such as **Invoice**, **Suspended**, etc. 
- The email body (HTML) is designed to match a trusting entity (such as Amazon)
- The email body (HTML) is poorly formatted or written (contrary from the previous point)
- The email body uses generic content, such as Dear Sir/Madam. 
- **Hyperlinks** (oftentimes uses URL shortening services to hide its true origin)
- A [malicious attachment](https://www.proofpoint.com/us/threat-reference/malicious-email-attachments) posing as a legitimate document


# HOW TO ANALYSE AN EMAIL

with the .eml file, open it with mousepad (or any textviewer/editor)
and also with thunderbird (or any other mail app) 

mousepad is useful to see all the header info (ip, sender, receiver, domain, html, ect)
thunderbird is useful to see the css + html and the overview of the mail

now we looking for the useful info :

- What is the email's timestamp?
- Who is the email from? is it a trusted source ? 
- What is his email address? 
- What email address will receive a reply to this email?
- What brand was this email tailored to impersonate?
- What is the originating IP?
- What do you think will be a domain of interest? 
- What is the shortened URL? 
- Do you think this is a phishing email?