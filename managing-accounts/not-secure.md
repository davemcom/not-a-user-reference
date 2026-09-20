# What Is Insecure

SMS codes are basically **temporary passwords delivered in plain text to a phone number**. If someone can read your messages, take over your mobile account, or move your number to another SIM, they can receive those codes too. Recovery email can have the same weakness if the email account is already open on an accessible device.

## **Targeted attacks** 
If someone believes you have money or valuable accounts, your phone number becomes an attack surface.
* **SMS:** readable bearer secret; whoever receives it can use it.
* **SIM swap / carrier takeover:** an attacker can sometimes convince or compromise the carrier into moving your number to their SIM or eSIM. SIM hijacking can be cheap—or free if social engineering succeeds—making SMS a particularly poor recovery mechanism for accounts valuable enough to target.
* **Email recovery:** often only as secure as the phone or computer already logged into that mailbox.
* **Weak device PIN:** may unlock SMS, email, password managers, and account recovery at once.
* **Password:** still vulnerable to reuse, phishing, keylogging, guessing, and database attacks.

## Recovery methods
These can be an accidential backdoor, where a weaker method could bypass stronger authentication methods.


**Strong authentication does not fix a weak recovery path.**
