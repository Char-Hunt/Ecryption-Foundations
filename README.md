# Ecryption-Foundations

BASIC CRYPTOGRAPHY

Understanding Symmetric-Key Algorithms

A Symmetric-Key Algorithm uses a string of data for encryption or decryption of information. This string performs like a real-world key which can unlock or lock a door. It is often referred to as a "key" or a "password". With symmetric-key algorithms, the same key is used for encrypting and for decrypting (This is why it's called "symmetric").

Anyone who knows or possesses the key can decrypt the information. Anyone who **does not know** or possess the key **cannot decryp**t it easily. It cannot be easily unscrambled like a substitution cipher. Someone would need to use advanced techniques to "break" the encryption.

If the algorithm is hard to break, it's a much better way to encrypt messages than a substitution cipher. Messages can be sent publicly, but only the recipient who is aware of the password can decrypt it. Much of the history of cryptography--even military communication/intelligence--has been dedicated towards either developing stronger algorithms or trying to break current algorithms.

The rapid increase of computing power beginning in the 1970s transformed the cryptography landscape. Hundreds of algorithms have been developed and hundreds have been broken, and underscore the need for cyber and IT security measures. There are three algorithms which are notable for their resistance to decryption and their wide-spread usage.

- The Data Encryption Standard (DES) algorithm was developed at IBM and first published in 1977. It was one of the first N.S.A. approved standards for encryption. It was widely used from 1977 until 2000. It was also widely studied and informs the design of later algorithms. However, it is now considered insecure. Modern computers can decrypt a DES encrypted message in less than a day. There is a successor to DES which is Triple DES (DES encyrption applied three times) which is still considered secure and is commonly used.

- The Advanced Encryption Standard (AES) algorithm was selected by the N.S.A. as the winner of an algorithm competition held in 2002. It is also known as "Rijndael" (pronounced rain-dahl) because that was its name during the competition. AES has not yet been broken is still considered strong enough to encrypt U.S. classified data.

- The Blowfish algorithm was designed in 1993. It has not yet been broken, even though a few technical and theoretical weaknesses have been identified. It is also widely used in many encryption software products. The feature that make Blowfish interesting is that it is slow compared to other encryption algorithms. This is a useful trait for password encryption.
#

Symmetric key algorithms are very fast and can encrypt large amounts of data.

The main drawback of symmetric key algorithms is distribution. Once a piece of data is locked or encrypted it can be sent publicly. However, the key or password must also be given to the recipient. The key is distributed to someone so that the information can be read. If the key is sent with the data or sent in plain text through another clearly visible channel, then it can be easily intercepted and the private data will be easily decrypted.

A known solution to this dilemma is to use symmetric key algorithms to encrypt the data and then to use asymmetric key algorithms (or "public key cryptography") to encrypt only the key which unlocks the encrypted information. This kind of [asymmetrical encryption](https://github.com/Char-Hunt/Learning-Info-Sec#types-of-encryption) is also known as a "non-identical key pair."
