Crack_Password_Goldman_Sachs

#Quoted by Goldman Sachs#

Overview

As a governance analyst it is part of your duties to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. To be successful at your job you often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of perimeter controls in place.

_______________________________________________________________________________________________________________________________________________________________

TASK

Crack as many passwords as possible with available tools (e.g. use Hashcat). Here are the Task instructions:

1. Review the links provided in the additional resources (section 4) below to gain a background understanding of password cracking
2. Try to crack the passwords provided in the 'password dump' file below using available tools
3. Assess the 5 questions in the task instructions below in relation to the passwords provided (type of hashing algorithm, level of protection, possible controls that could be implemented, password policy, changes in policy)
4. Draft an email/memo briefly explaining your findings in relation to controls used by the organization and your proposed uplifts. We recommend spending about 1.5 hours on this task and keeping it at 1 page in length. 
5. Your answer should be provided in the form of a draft email/memo explaining your findings and conclusions of controls currently used by an organization to prevent successful cracking of passwords and potential uplifts that you would propose to existing controls with justifications.

Raw File - [Raw_Report.docx](https://github.com/shiwanisabnis/Crack_Password_Goldman_Sachs/files/8865851/Raw_Report.docx)

#UnQuote#
______________________________________________________________________________________________________________________________________________________________

Solution and Conclusions

After making all the analyses using Hashcat Tool and other hash identifiers like hashes.com, crackhash.com - it has been found that all the passwords contain MD5 hash function. This make the passwords weak and can easily be hacked. 
Bare minimum requirement of standard cryptographic hash functions which are Secure Hash Algorithm (SHA) like SHA-256 and SHA-3 & Message Digest (MD5) should be use to maintain the security of passwords. 

I would like to suggest some controls which should be implemented for making the cracking harder:
1.	Setting a minimum length password rule.
2.	Passwords should always contain special characters, Uppercase-Lowercase alphabets, numbers.
3.	Password Salting concept and using strong hashing algorithm should be implemented.

It has been observed that there is no as such rule regarding the minimum length of the password to be used and no force over user for adding special characters in the password.

Kindly note that most of the passwords were generated with easy of keyboard setup – Like the series of set alphabet and characters on keyboard.
Hence, password policies should be updated keeping the below points in mind -
1.	Password must be of minimum 8-10 characters.
2.	Should not use common words.
3.	Should not allow reusing the old passwords.
4.	Should not let user to add series of numbers like 1234, 0000, abcd or wxyz etc.
5.	Should showcase the strength of password using an external API.
6.	Users should have warning message on screen for showing minimum requirement for designing any password.

_______________________________________________________________________________________________________________________________________________________________

Full Report - 

[Report_for_Crack_leaked_password_database.pdf](https://github.com/shiwanisabnis/Crack_Password_Goldman_Sachs/files/8865812/Report_for_Crack_leaked_password_database.pdf)

______________________________________________________________________________________________________________________________________________________________

Referencing 

https://howsecureismypassword.net/

https://en.wikipedia.org/wiki/Password_cracking#Software

https://en.wikipedia.org/wiki/Salt_(cryptography)

https://hashcat.net/hashcat/

https://crackstation.net/

https://hashes.com/en/decrypt/hash
