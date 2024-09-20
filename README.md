# breachedWebsitesList 🚧💥🔓
A list of domains where the user database was breached and user emails were stolen for email spam.

## 🔎 How we track
1 We register a user with unique email address on each tracked domain.  
2 We wait to recieve spam.  
3 We check the recipient address to determine the breached domain.  
4 If sender domain does not match the domain where we left our email address, we know the database has been breached.

## ⚔️ After detection
1 We notify the website hosted on the domain about possible breach.  
2 Cooperate with the website to manage the breach better.  
3 Disclose the breach publicly on GitHub.

## 🕹️ Example explanation
We will (play-pretend) track the breach of (made up) normalshop-bwl.com. All domains are made up.  
We prepared an emailserver at ourserver-bwl.org where we can read incoming mail.  
The normalshop-bwl.com is a legitimate web store.  
1 We register a regular user account at normalshop-bwl.com with email 4w7792w4qpmiyzeh@ourserver-bwl.org.  
This email was not used anywhere else! Only the normalshop-bwl.com and us know it.  
2 We receive mail from penisenlargementpump@spammer-bwl.net.  
This is a spam email. It contains no references to normalshop-bwl.com. We know nothing about the spammer-bwl.net domain.  
3 The mail was sent to 4w7792w4qpmiyzeh@ourserver-bwl.org, therefore it must have been acquired from normalshop-bwl.com.  
4 Sender is not normalshop-bwl.com, therefore the normalshop-bwl.com was breached.
