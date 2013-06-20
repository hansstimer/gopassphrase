gopassphrase
===

Generates passphrases of varying levels of security.

Given the large number of exposed passwords, it is no longer safe to select your own password or passphrase. You are human, and you are predictable, given a large enough sample size. Only random passwords and passphrases are safe at this point.

Not all websites accept passphrases, in which case you need a random password. 

The best way to decide how much security you need is by how much it would cost someone to break your password. 

    bits	cost to break*
    ---		-------------
     15 	< USD 0.01
     30		< USD 0.01
     45		< USD 0.01
     60		USD 200
     75		USD 6.5M
     80 	USD 210M (NIST recommendation)
     90		USD 215B
    105		USD 7,000T
    * In 2013 assumes USD 0.01/trillion combinations, using custom ASICs and USD 0.10/KWH
    ** Cost should halve every 2 years, and it is reported that quantum computers wont make much difference for this kind of problem

Suggestions for passwords:
---
* You may not know what many of the words mean, but don't search for their meaning on the net because your searches are recorded. If you really need to know, go to the library and look it up, or use a downloaded dictionary or Wikipedia. Just make sure they don't do searches across the net.
* Don't take a weak passphrase that you are using and try and make it strong by adding a word or two. That can be targeted, instead, create a new phrase.
* You can easily add 6 bits of complexity to a passphrase by appending a 2 digit number; this is useful for making a passphrase 100x more expensive to break.
* You don't need to use this program to create a random passphrase. Selecting words randomly from a dictionary works well. Selecting random words from a book or newspaper is not advisable, because of the very small selection of unique words and the uneven distribution.

Recommendations on keeping your computer secure
---
* Use a 75 bit passphrase for your finances i.e. anyone you give your credit card to, banks, brokerages, and email
* Use a 60 bit passphrase for non critical web sites
* Use a 60 bit passphrase for your desktop, if your hard drive is encrypted; otherwise use a 75 bit one
* Use a password manager to keep track of unique passwords for each website that matters to you
* Keep your passwords in a physical address book; a small one that you can keep in your wallet along with your money
* Use a secure OS: OSX>Win, OpenBSD>FreeBSD>NetBSD>Linux, IOS>WP>Android
* Use the current version of your favorite OS
* Keep your OS patched
* Use a modern browser and keep it patched - Opera>Chrome>Firefox>IE>Safari
* Don't use Flash in your browser, but if you have to have it, then use Chrome because it is built in and sandboxed
* Keep all your applications patched
* Don't fall for phishing scams; assume any url in an email is bogus and will send you to a phishing site
* Never use an application sent to you in an email
* Never open documents sent to you from people you don't know
* Only run applications that are signed and sandboxed
* Keep your data backed up in multiple locations
* When it is time to make a major OS upgrade (hopefully, yearly), backup, zero your OS drive, reinstall the OS and all Applications from scratch, then transfer your data back. Use a new passphrase.
