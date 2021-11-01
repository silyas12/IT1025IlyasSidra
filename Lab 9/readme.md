# Executive Summary

 You will learn about Cybersecurity and Encryption. What ACL and RBAC is and the pros and cons of each. You will learn to do some cryptography. 

Cybersecurity and Encryption

* Imagine you are part of the Amazon.com online chat. Explain how each component of the security triad would impact your job

 Confidentiality – Keeping sensitive information private. Encryption services can protect your data at rest or in transit and prevent unauthorized access to protected data.
Integrity – is the consistency of data, networks, and systems. This includes mitigation and proactive measures to restrict unapproved changes, while also having the ability to recover data that has been lost or compromised.
Availability – refers to authorized users that can freely access the systems, networks, and data needed to perform their daily tasks. Resolving hardware and software conflicts, along with regular maintenance is crucial to keep systems up and available.
As an amazon worker, I would have to make sure I maintain the integrity by making sure all data is consistent. I will make sure that users have availabilty to the website and all the other resources associated with the amazon. Lastly, I will maintain confidentiality by keeping things private and making sure customers and employess only have access to what they are allowed to. 
 
* Identify three daily tasks that require authentication. Explain how each one could be converted to multi-factor authentication

  Type 1 – Something You Know – includes passwords, PINs, combinations, code words, or secret handshakes.
  Type 2 – Something You Have – includes all items that are physical objects, such as keys, smart phones, smart cards, USB drives, and token devices.
  Type 3 – Something You Are – includes any part of the human body that can be offered for verification, such as fingerprints, palm scanning, facial recognition, retina scans, iris scans, and voice verification.
  By combining two or three factors from these three categories, a multi-factor authentication is crafted. Multi-factor authentication is preferred, as it is much more difficult for an intruder to overcome. With just a password, an attacker only has to have a single attack skill and wage a single successful attack to impersonate the victim. With multi-factor authentication, the attack must have multiple attack skills and wage multiple successful attacks simultaneously in order to impersonate the victim. This is extremely difficult and, thus, a more resilient logon solution.
  
* Explain ACL and RBAC. What are the advantages and disadvantages of each?

    ACL is better suited for implementing security at the individual user level and for low-level data, while RBAC better serves a company-wide security system with an overseeing administrator. An ACL can, for example, grant write access to a specific file, but it cannot determine how a user might change the file.
    
* Explain the interaction of ciphertext, a public key and a private key

  In Private key, the same key (secret key) is used for encryption and decryption. In this key is symmetric because the only key is copy or share by another party to decrypt the cipher text. It is faster than the public key cryptography. In Public key, two keys are used one key is used for encryption and another key is used for decryption. One key (public key) is used for encrypt the plain text to convert it into cipher text and another key (private key) is used by receiver to decrypt the cipher text to read the message.  
* Explain why we need public key cryptography.

  Public key cryptography remains the most secure protocol (over private key cryptography) because users never need to transmit or reveal their private keys to anyone, which lessens the chances of cyber criminals discovering an individual's secret key during the transmission

## Cryptography
* Type a message in the "Caesar Cipher Exploration box and turn the wheel to encrypt your message.
Then explain the encryption here:

  I wrote life is hard. It returned jgdc gq fypb. Here my original message shifted by two letters. Each letter applies a shift of number of leters they decide on like 3 for example 
* Type a message in the "Frequency Fingerprint Exploration" box and a) Explain the result.

  I wrote I am learning to program. I saw the frequency go up for some letters and more I wrote the frequency rose higher. 
b) Would it be different for different languages?
Yea, it would be because other languages would use letters differently. 
* What is a "Polyalphabetic cipher?"
Type a message in the "Polyalphabetic Exploration" box as well as a shift word.
Explain the result.

  I wrote I like it. It gave me j dclw cu and my shift word is art. So the way code works is used the order of alphabet on art. ART would be 1,18,20. So the letters would shift by 1,18,20 each time and it repeats. 

## Brute Force
* What is Brute-Force and how does it relate to Kerckhoffs's principle?
  
   Brute force attacks are simple and reliable. Attackers let a computer do the work – trying different combinations of usernames and passwords, for example – until they find one that works. Kerckhoffs' Principle states that the security of a cryptosystem must lie in the choice of its keys only; everything else (including the algorithm itself) should be considered public knowledge.
# Conclusion
Summarize how this lab was useful to you and what you learnt that really interested you!
 
   I learned about encription and how it's used to keep data secure. I learned about brute force, cybersecurity and lot more.
